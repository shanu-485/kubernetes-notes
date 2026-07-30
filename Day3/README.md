# Kubernetes Day 3

## Topics Learned

- Deployment
- ReplicaSet
- Scaling
- Self Healing
- kubectl scale
- kubectl describe

## YAML File

- nginx-deployment.yaml

## Commands Practiced

```bash
kubectl apply -f nginx-deployment.yaml
kubectl get deployments
kubectl get replicasets
kubectl get pods
kubectl scale deployment nginx-deployment --replicas=5
kubectl scale deployment nginx-deployment --replicas=2
kubectl describe deployment nginx-deployment
kubectl delete deployment nginx-deployment
```

## Key Learnings

- Deployment manages Pods automatically.
- ReplicaSet maintains the desired number of Pods.
- Scaling changes the number of running Pods.
- Kubernetes automatically recreates Pods if they fail.

