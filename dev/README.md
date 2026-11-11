# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 62730a13c2b144375591a5110b4772df0949fc17
kustomize build ./environment/dev
```
