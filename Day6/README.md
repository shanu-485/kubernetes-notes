# Kubernetes Day 6

## Topics Learned

- Persistent Volume (PV)

- Persistent Volume Claim (PVC)
- Volume Mounts
- Persistent Storage

## Files

- pv.yaml
- pvc.yaml
- nginx-pvc.yaml

## Commands Practiced

```bash
kubectl apply -f pv.yaml
kubectl get pv

kubectl apply -f pvc.yaml
kubectl get pvc

kubectl apply -f nginx-pvc.yaml
kubectl get pods

kubectl describe pvc my-pvc

kubectl delete pod nginx-pvc
kubectl delete pvc my-pvc
kubectl delete pv my-pv
```

## Key Learnings

- Persistent Volumes (PV) provide durable storage.
- Persistent Volume Claims (PVC) request storage from Kubernetes.
- Pods can use PVCs to retain data even if they are recreated.
