
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout 721fa2fea2d9173797bb19f1c3eb8c7e47499f47
kustomize build ./staging/integration
```