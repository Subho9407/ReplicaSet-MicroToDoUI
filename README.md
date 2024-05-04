# ReplicaSet-MicroToDoUI


# Pods:

# To deploy Pod
kubectl apply -f pod.yaml
# To get running pods
kubectl get pods
# Port forwarding to check
kubectl port-forward pod/todo-ui-pod 8085:80 

# ReplicaSet:

# To deploy ReplicaSet
kubectl apply -f rs.yaml #To deploy ReplicaSet
# To get running ReplicaSets
kubectl get rs 
# Port forwarding to check
kubectl port-forwards pod/todo-controller-5hxrp 8084:80
