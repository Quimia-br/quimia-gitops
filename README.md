# quimia-gitops
## Quimia GitOps

Estrutura inicial para sincronização pelo ArgoCD.

- `apps/quimia-api/base`: recursos comuns da API.
- `apps/quimia-api/overlays/dev`: imagem e namespace do ambiente de desenvolvimento.
- `argocd/applications`: definições das Applications ArgoCD.
