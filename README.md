# kubernetes

### How to use k8s (minikube)
#### 1.Install minikube
```
install minikube
```
#### 2.Create cluster node
```
minikube --help
```
```
minikube start --nodes=2
```

#### K8s dashboard
```
minikube dashboard
```
#### check node
```
kubectl get node
```
#### check pods
```
kubectl get pod
```
#### check service
```
kubectl get svc
```
```
kubectl get service
```

#### check deploy
```
kubectl get deploy
```

#### apply 
```
kubectl apply -f finename.yaml
```
### ingress
#### 1.install
```
sudo apt install helm
```
```
choco install kubernetes-helm
```
```
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
```
```
kubectl apply -f ingress.yaml
```
