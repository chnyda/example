# example

# create storage class
kubectl create -f sc.yaml
# create pvc
kubectl create -f pvc.yaml
# create pod using pvc ^
kubect create -f pod.yaml
