
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout 5ae990a78b2ac16f94fe178dca07b26e4a1161a2
kustomize build ./staging/integration
```