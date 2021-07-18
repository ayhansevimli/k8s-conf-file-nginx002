# k8s-conf-file-nginx002

cd C:\Utils\DevOps\Containerisation\kubernetes

git clone https://github.com/ayhansevimli/k8s-conf-file-nginx002.git

cd k8s-conf-file-nginx002

kubectl apply -f k8s-conf-file-nginx002-deployment.yaml

kubectl get deployment

kubectl get pod

kubectl get replicaset

kubectl get service

kubectl apply -f k8s-conf-file-nginx002-service.yaml

kubectl get deployment

kubectl get pod

kubectl get replicaset

kubectl get service

kubectl get pod -o wide

-Get more information deployment and service.

kubectl describe deployment k8s-conf-file-nginx002-deployment

kubectl describe service k8s-conf-file-nginx002-service



-Delete deployments.

kubectl delete -f k8s-conf-file-nginx002-deployment.yaml

kubectl delete -f k8s-conf-file-nginx002-service.yaml

kubectl get deployment

kubectl get pod

kubectl get replicaset

kubectl get service

kubectl get pod -o wide

