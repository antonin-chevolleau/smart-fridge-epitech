# 🤝 Conventions de travail

Ces règles s'appliquent aux 3 membres de l'équipe. Le sujet exige que chaque modification soit lisible dans
l'historique des commits : une branche et une PR par tâche.

## 🌿 Branches

Format : `type/Txx-slug`, créée depuis `main` à jour.

| Type    | Usage                                  | Exemple                 |
| ------- | -------------------------------------- | ----------------------- |
| `docs`  | Rédaction ou mise à jour d'un livrable | `docs/T07-cadrage`      |
| `chore` | Organisation, outillage, suivi         | `chore/T01-setup-suivi` |
| `fix`   | Correction (lien mort, chiffre, faute) | `fix/T26-liens`         |

- Une tâche = une branche = une PR. Si une tâche est partagée, chacun travaille sur sa branche
  (`docs/T10-gantt-antonin`).
- On ne pousse jamais directement sur `main`.
- Les branches personnelles `TK` et `xavier` ne sont plus utilisées.

## ✍️ Commits

[Conventional Commits](https://www.conventionalcommits.org/) en minuscules, à l'impératif, avec l'ID de tâche
en portée :

```
docs(T07): add scope and out-of-scope sections
chore(T01): add contributing guide
fix(T26): repair broken links in README
```

- Un commit = une modification cohérente et lisible.
- Les documents itératifs (Gantt, budget, risques) : un commit par version, avec la raison du changement dans
  le message.

## 🔀 Pull requests

- Titre : `Txx : titre de la tâche`.
- Description : ce qui a changé, pourquoi, critère de fin de la tâche (voir
  [`task-breakdown.md`](docs/planning/task-breakdown.md)).
- Au moins **1 relecture** d'un autre membre avant fusion (`CODEOWNERS` assigne la relecture).
- Fusion sur `main` **au plus tard à l'échéance** du [planning](docs/planning/planning.md).
- Après la fusion : cocher la tâche dans [`tasks.md`](docs/planning/tasks.md) et supprimer la branche.

## 📂 Arborescence des livrables

| Dossier                   | Contenu                                                          | Tâches        |
| ------------------------- | ---------------------------------------------------------------- | ------------- |
| `docs/project/`           | Sujet officiel et traduction                                     | —             |
| `docs/planning/`          | Découpage, estimation, planning, suivi des tâches                | T01–T04       |
| `docs/cadrage/`           | Hypothèses, veille, cadrage, plan de recherche, feuille de route | T05–T09       |
| `docs/pmp/gantt/`         | Gantt (`.xlsx`, exports) et journal des révisions                | T10, T11, T20 |
| `docs/pmp/ressources/`    | Rôles, personas, ressources matérielles                          | T13–T15       |
| `docs/pmp/budget/`        | Fourchettes de prix et budget                                    | T16, T17      |
| `docs/pmp/risques/`       | Registre des risques et imprévus simulés                         | T18, T19      |
| `docs/pmp/communication/` | Communications interne et exécutive                              | T22, T23      |
| `docs/pmp/`               | Document maître du PMP et stratégie de production                | T12, T21      |
| `docs/revue/`             | Journal des difficultés, slides de soutenance                    | T24, T28      |

Nommage : minuscules, sans accents ni espaces, tirets (`plan-de-recherche.md`).
