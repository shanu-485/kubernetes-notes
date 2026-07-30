# Kubernetes Day 4

## Topics Learned

- Services
- ClusterIP
- NodePort
- Minikube Service
- Kubernetes Networking

## Files

- nginx-deployment.yaml
- nginx-service.yaml

## Commands Practiced

```bash
kubectl apply -f nginx-deployment.yaml
kubectl apply -f nginx-service.yaml
kubectl get services
minikube service nginx-service
kubectl delete service nginx-service
kubectl delete deployment nginx-deployment
kubectl get all
```

## Key Learnings

- Services provide a stable endpoint for Pods.
- NodePort exposes an application outside the cluster.
- Minikube can expose services locally using a tunnel.

