# Kubernetes Day 7 - Final Mini Project


## Topics Covered

- Deployment
- Service
- ConfigMap
- Secret
- Persistent Volume (PV)
- Persistent Volume Claim (PVC)

## Files

- deployment.yaml
- service.yaml
- configmap.yaml
- secret.yaml
- pv.yaml
- pvc.yaml

## Commands Practiced

```bash
kubectl apply -f pv.yaml
kubectl apply -f pvc.yaml
kubectl apply -f configmap.yaml
kubectl apply -f secret.yaml
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

kubectl get all
kubectl get pv
kubectl get pvc

minikube service nginx-service

kubectl delete -f .
```

## Key Learnings

- Combined all major Kubernetes resources into one project.
- Used Deployments to manage Pods.
- Exposed the application using a Service.
- Stored configuration with ConfigMaps.
- Stored sensitive data with Secrets.
- Attached persistent storage using PV and PVC.
