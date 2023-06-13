# KUBERNETES

K8's is an open-source container orchestration system for automating software deployment, scaling, and management.

## K8's cmds

```
kubectl get pod
kubectl explain pod
kubectl apply -f pod.yaml
kubectl delete pod pod-name
kubectl port-forward nginx-k8s 8080:80
kubectl exec -it -c container1/2 pod_name --bash
kubectl exec -it pod_name curl ip_address
kubectl get deployments
kubectl scale deployment example-deplyment --replicas=4(or we can update in deployment.yaml file)
kubectl rollout history deployment/example-deplyment
kubectl rollout history deployment/example-deplyment --revision=1
kubectl rollout undo deployment example-deplyment --to-revision=1
kubectl delete deployment example-deplyment
kubectl get pods -o wide
```
