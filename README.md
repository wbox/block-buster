# Flux-cd Udemy Training

## Install flux-cd
```text
 curl -s https://fluxcd.io/install.sh | sudo bash
```

## Bootstrap flux-cd pn the cluster
```text
flux bootstrap github \
  --token-auth \
  --owner=my-github-username \
  --repository=my-repository-name \
  --branch=main \
  --path=clusters/my-cluster \
  --personal=true
  --private=false
```
