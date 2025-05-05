
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout 254505a45c4b7448de15c0fbbd65ffb6c6087c58
kustomize build ./staging/integration
```