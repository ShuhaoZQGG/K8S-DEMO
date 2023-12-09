# Steps to deploy the k8s locally using minikube:
```powershell
1. kubectl appply -f <configmap_file>
2. kubectl apply -f <secret_file>
3. kubectl apply -f <deployment_file>
```

# To check status:
```powershell
kubectl get all
kubectl get pod
kubectl get service
kubectl describe service <service_name>
kubectl describe pod <pod_name>
```
# check minikube ip:
```bash
minikube ip
```

# In case cannot access to minikube ip using windows:
```bash
kubectl service <service_name>
```
