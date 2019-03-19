`kubectl get deployment examplehttpapp -o yaml`{{execute}}

`kubectl get deployment examplehttpapp -o yaml --export`{{execute}} (Thanks [Heptio](https://blog.heptio.com/using-kubectl-to-jumpstart-a-yaml-file-heptioprotip-6f5b8a63a3ea))

`kubectl get deployment examplehttpapp -o yaml --export > examplehttpapp.yaml`{{execute}}

`kubectl create deployment my-cool-app --image=me/my-cool-app:v1 -o yaml --dry-run`{{execute}}

`vim examplehttpapp.yaml`{{execute}}
