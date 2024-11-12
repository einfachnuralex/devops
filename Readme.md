
## Install Ingress | Cert-Manager

```bash
kubectl kustomize ./base/ingress | EMAIL="email_address" envsubst | kubectl apply -f -
```

