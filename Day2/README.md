# Kubernetes Day 2

## Topics Learned

- Pods
- YAML
- kubectl apply
- kubectl get
- kubectl describe
- kubectl logs
- kubectl exec
- kubectl delete

## Commands Practiced

```bash
kubectl apply -f nginx-pod.yaml
kubectl get pods
kubectl describe pod nginx-pod
kubectl logs nginx-pod
kubectl exec -it nginx-pod -- sh
kubectl delete pod nginx-pod
```

## Key Learnings

- A Pod is the smallest deployable unit in Kubernetes.
- YAML files define Kubernetes resources.
- kubectl is used to create, inspect, and manage Pods.

