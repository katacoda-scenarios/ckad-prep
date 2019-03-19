`kubectl create ns testns`{{execute}} `kubectl create deployment namespacedexamplehttpapp -n testns --image=katacoda/docker-http-server`{{execute}} 

`kubectl get pods -n testns`{{execute}}

Pro tip: `kubectl config set-context $(kubectl config current-context) --namespace=testns; kubectl config get-contexts`{{execute}}