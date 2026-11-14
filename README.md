# ArgoCD version
v3.6.1 non-HA

## Installation command
```bash
kubectl apply -n argocd --server-side --force-conflicts -f https://raw.githubusercontent.com/argoproj/argo-cd/v3.6.1/manifests/install.yaml
```

# DEX scaled to zero
```bash
kubectl scale deploy argocd-dex-server -n argocd --replicas=0
```
