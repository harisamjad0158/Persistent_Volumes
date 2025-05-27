echo -m "Admin123" | base64

kubectl logs pod/mysql-deployment-549c8ff445-6tqjb -n mysql

kubectl get secrets -n mysql

MySQL Kubernetes Deployment

Encode Password (Base64)
```bash
echo -n "Admin123" | base64


kubectl apply -f namespace.yml
kubectl apply -f secrete.yml
kubectl apply -f deployment.yml
kubectl get pods -n mysql

kubectl get secrets -n mysql
kubectl get pods -n mysql -w

kubectl exec -it mysql-deployment-b64d994cf-ddw5b -n mysql -- bash
> mysql -u root -p
> MyAdmin123
> show databases;



