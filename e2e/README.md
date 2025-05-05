
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout 384d538cbc2b1de643823e380f3988742edd3327
kustomize build ./staging/e2e
```