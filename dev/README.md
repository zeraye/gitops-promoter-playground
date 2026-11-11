# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 9f94c8f4626a3b292e97c7969af2471e809d4ae1
kustomize build ./environment/dev
```
