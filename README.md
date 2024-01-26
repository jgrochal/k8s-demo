# A k8s demo

##  Basic approach

Commands to run WP deployment:

```
minikube start --nodes 2
kubectl apply -k ./
minikube service wordpress --url
```

URL will lead to WP dashboard and after the installation the WP CMS can be used.
