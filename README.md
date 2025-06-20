# Kubernetes

To run:

```
kubectl apply -f ./deployment.yaml
kubectl apply -f ./service.yaml
```

To list:

```
kubectl get pods
kubectl get svc
```

To access:

```
kubectl get nodes -o wide
```

Copy internal-ip from minikube and past in browser with port 30000
