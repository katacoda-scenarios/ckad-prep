Logs?

`kubectl logs $(kubectl get pods -l app=examplehttpapp -o go-template='{{(index .items 0).metadata.name}}')`{{execute}}