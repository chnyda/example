# example
git clone https://github.com/chnyda/example
# create storage class
kubectl create -f $(pwd)/example/sc.yaml
# create pvc
kubectl create -f $(pwd)/example/pvc.yaml
# create pod using pvc ^
kubect create -f $(pwd)/example/pod.yaml
