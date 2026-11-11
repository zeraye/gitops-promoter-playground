# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout b5c9509ee58985f6303ee271131a6a51e9596c95
kustomize build ./environment/dev
```
