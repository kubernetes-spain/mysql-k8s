# mysql-k8s

# Deploy
```
git clone https://github.com/kubernetes-spain/mysql-k8s.git
cd mysql-k8s
kubectl apply -f mysql-secret.yaml
kubectl apply -f mysql-storage.yaml
kubectl apply -f mysql-deployment.yaml
```


# Eliminar
```
kubectl delete deployment,svc mysql
kubectl delete pvc mysql-pv-claim
kubectl delete pv mysql-pv-volume
kubectl delete secret mysql-secret
```

