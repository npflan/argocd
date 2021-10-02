# ArgoCD - Deployment management

# Usage

Start by deploying ArgoCD
```
kubectl apply -f manifests/argocd.yaml
```

Deploy infrastrucure project
```
kubectl apply -f manifests/infrastructure.yaml
```

Add Application to Argo
```
kubectl apply -f manifests/argocd-app.yaml
```
