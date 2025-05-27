kubectl apply -f namespace.yml

kubectl apply -f mysql-pv.yml

kubectl apply -f mysql-pvc.yml

kubectl apply -f secret.yml

kubectl apply -f configMap.yml

kubectl apply -f deployment.yml

kubectl get pvc -n mysql

kubectl get pv

 kubectl get pvc

kubectl describe pod mysql-deployment-5556fff6cc-7vppd  -n mysql

docker ps

docker exec -it 03eb50b504cd bash

	cd /mnt/data/mysql
