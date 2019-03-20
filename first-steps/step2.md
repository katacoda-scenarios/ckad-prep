Kubernetes is managed by creating, editing or updating objects and resources. Each object defines a structure and properties that instructs Kubernetes to make changes to the current state. To deploy an applicaton, a Deployment needs to be created using `kubectl create deployment examplehttpapp --image=katacoda/docker-http-server`{{execute}} 

View all deployments with `kubectl get deployments`{{execute}}

