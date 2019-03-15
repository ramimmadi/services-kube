$  kubectl run web --image=gcr.io/google-samples/hello-app:1.0 --port=8080
to test the functionality of cluster ip, you need to use curl since works only through browser, But to curl will not be pre-installed in the containers so we need to use commands
$  apk update
$  apk add curl

