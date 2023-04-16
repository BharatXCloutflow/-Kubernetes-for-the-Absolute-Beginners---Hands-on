kubectl get replicaset
kubectl delete replicaset name
kubectl replace -f replicaset.yaml
kubectl scale --replicas=6 replicaset.yaml
kubectl edit replicaset myapp-rc
