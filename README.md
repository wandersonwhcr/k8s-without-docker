# iac

```
kubectl apply \
  --file https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.41.2/deploy/static/provider/baremetal/deploy.yaml

kubectl apply \
  --file https://github.com/jetstack/cert-manager/releases/download/v1.1.0/cert-manager.yaml

kubectl apply --kustomize overlays/builder
```
