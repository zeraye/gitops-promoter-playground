# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 124bf287f0d73307f4047232d69321908e2522d9
kustomize build ./environment/dev
```
