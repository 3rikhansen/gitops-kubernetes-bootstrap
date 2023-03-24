
https://docs.k3s.io/storage

kubectl apply -f https://raw.githubusercontent.com/longhorn/longhorn/master/deploy/longhorn.yaml

kubectl create -f pvc.yaml
kubectl create -f pod.yaml