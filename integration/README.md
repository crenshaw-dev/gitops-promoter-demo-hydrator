
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout ce8c7a55cf45d93c8dedf49bd07140a16c407f1a
kustomize build ./staging/integration
```