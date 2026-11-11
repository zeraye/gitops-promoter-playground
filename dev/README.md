# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 774869c46b3e2c8cc77d3c503128bf1c5c32793b
kustomize build ./environment/dev
```
