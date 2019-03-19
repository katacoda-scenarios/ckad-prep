By default, Pods are started within the default namespace. List all namespaces with`kubectl get namespaces`{{execute}}. The namespaces can be used to filter queries to the available objects. `kubectl get pods -n kube-system`{{execute}}

Pro Tip: Use the shorthand `kubectl get ns`{{execute}}
