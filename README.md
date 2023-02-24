Pour appliquer, avec env = sandbox|integration|recette
```
kustomize build application/overlay/<env> | kubectl apply -f -
```