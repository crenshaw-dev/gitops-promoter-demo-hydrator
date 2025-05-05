
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout 1ac7654a2973bbbc20f528f3f5418630e62c63df
kustomize build ./staging/integration
```