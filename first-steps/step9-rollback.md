**Mistakes happen!** Likewise with Rollout status, it can be rolled back to the previous version using `kubectl rollout undo deployment examplehttpapp`{{execute}}

A history of all the updates can be viewed with `kubectl rollout history deployment examplehttpapp --revision=1`{{execute}}
