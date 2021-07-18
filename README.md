# k8s-conf-file-nginx002

cd C:\Utils\DevOps\Containerisation\kubernetes

git clone https://github.com/ayhansevimli/k8s-conf-file-nginx002.git

cd k8s-conf-file-nginx002

kubectl apply -f k8s-conf-file-nginx001.yaml

kubectl get deployment

kubectl get pod

kubectl get replicaset


-Change replicaset to 2 in yaml file and apply again.

kubectl apply -f k8s-conf-file-nginx001.yaml

kubectl get deployment

kubectl get pod

kubectl get replicaset

