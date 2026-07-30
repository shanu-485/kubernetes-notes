# Kubernetes Day 5

## Topics Learned

- ConfigMap
- Secret
- Environment Variables

## Files

- configmap.yaml
- secret.yaml

## Commands Practiced

```bash
kubectl apply -f configmap.yaml
kubectl get configmaps
kubectl describe configmap app-config

kubectl apply -f secret.yaml
kubectl get secrets
kubectl describe secret app-secret

kubectl delete -f configmap.yaml
kubectl delete -f secret.yaml
```

## Key Learnings

- ConfigMaps store non-sensitive configuration.
- Secrets store sensitive information.
- Applications can use ConfigMaps and Secrets through environment variables or mounted files.

