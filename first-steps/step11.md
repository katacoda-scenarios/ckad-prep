label select svc to get IP

`curl $(kubectl get services -l app=examplehttpapp -o go-template='{{(index .items 0).spec.clusterIP}}')`{{execute}}

View the response schema - `kubectl get services -l app=examplehttpapp -o json`{{execute}}

