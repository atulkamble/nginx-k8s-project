```
aws eks update-kubeconfig --name mycluster --region us-east-1

git clone https://github.com/atulkamble/nginx-k8s-project.git
cd nginx-k8s-project

kubectl apply -f deployment.yaml
kubectl apply -f daemonset.yaml 
kubectl get pods -o wide 
kubectl get pods 
kubectl delete pod pod-id 
kubectl get pod -o wide 

kubectl scale deployment nginx --replicas=8
```
