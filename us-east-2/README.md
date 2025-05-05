
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout bc284fc3b1a3d038607444262d7db3a40ede621b
kustomize build ./production/us-east-2
```