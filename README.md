echo -m "Admin123" | base64
kubectl logs pod/mysql-deployment-549c8ff445-6tqjb -n mysql
kubectl get secrets -n mysql
