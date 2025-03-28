# external-secrets-operator-demo
external-secrets-operator-demo

https://external-secrets.io/latest/introduction/getting-started/

kubectl -n external-secrets create secret generic vault-token --from-literal=token=<TOKEN>

```bash
helm repo add external-secrets https://charts.external-secrets.io

helm install external-secrets \
   external-secrets/external-secrets \
    -n external-secrets \
    --create-namespace \
  # --set installCRDs=false
```

# external-secret
https://external-secrets.io/v0.4.4/api-externalsecret/
