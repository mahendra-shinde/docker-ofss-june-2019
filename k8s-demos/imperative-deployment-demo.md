## Imperative Deployment (ie. deployment using CLI)

## Create a new deployment "web1" which contains one "ReplicaSet" 
## ReplicaSet contains "Pods"
## "Pods" contains Containers

$ kubectl create deployment web1 --image=nginx:1.7.9   

# Check the deployments 
$ kubectl get deployments

# Check the replicasets
$ kubectl get replicasets

# check the Pods
$ kubectl get Pods

# check the Containers
$ docker ps 