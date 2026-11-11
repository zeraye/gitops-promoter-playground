# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zeraye/gitops-promoter-playground
# cd into the cloned directory
git checkout 61ad5d3b80a5bd94c0ef5529b10afbe16c014706
kustomize build ./environment/dev
```
