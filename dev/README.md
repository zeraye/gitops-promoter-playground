# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 9919e4729af4327e6d5400b45f840b90adf10e28
kustomize build ./environment/dev
```
