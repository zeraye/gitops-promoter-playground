# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 48893ef195685c9cc38a18f9209a061cdb172f5a
kustomize build ./environment/dev
```
