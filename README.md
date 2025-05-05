
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/crenshaw-dev/gitops-promoter-demo-hydrator
# cd into the cloned directory
git checkout e567aadeb1040d7e68d9d57a760fb4936c9e2c63
kustomize build ./development
```