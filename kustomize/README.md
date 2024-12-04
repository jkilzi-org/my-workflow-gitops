# kustomize deployment of F05EB00E.D9D7.46B1.BC27.136EB02E22E1
## Configure the deployment
Add the deployment variables to [config.properties](./base/config.properties) and [secret.properties](./base/secret.properties) to
configure the deployment environment.

## Install
Install the deployment in the default namespace:
```bash
kustomize build base | oc apply -f -
```

## Uninstall
Remove the deployment resources:
```bash
kustomize build base | oc delete -f -
```
