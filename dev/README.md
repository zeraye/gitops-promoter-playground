# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 93028d5f1c339337af2e49953c76bdf191c79152
kustomize build ./environment/dev
```
