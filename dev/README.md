# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 0ac298782ca191d995b7d68d3feb731d812d4fb7
kustomize build ./environment/dev
```
