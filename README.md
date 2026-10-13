# menuFood .github

Arquivos padrão da organização **menuFood** no GitHub. Os modelos de issue em `.github/ISSUE_TEMPLATE/` valem para todos os repositórios da organização que não têm `.github/ISSUE_TEMPLATE/` próprio.

| Modelo | Título | Labels |
|---|---|---|
| `bug.yml` | `[Bug]: ` | `bug`, `triagem` (tipo Bug) |
| `feature.yml` | `[Feature] - ` | `enhancement`, `triagem` (tipo Feature) |

Os dois têm o campo obrigatório **Projeto**, que indica o repositório onde o trabalho vai ser feito (`menu_food`, `bina-app`, `chama-garcom` ou `marketing`). Ao incluir um projeto novo na organização, acrescente a opção nos dois modelos.

O label `triagem` marca a issue recém-aberta que ainda não foi analisada. Remova-o ao mover o card para Backlog ou Todo no kanban da organização.

Este repositório precisa ser **público** para o GitHub aplicar os modelos aos demais repositórios. Não coloque nada sigiloso aqui.
