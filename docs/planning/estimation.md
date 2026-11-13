# ⏱️ Estimation des tâches

> **Statut** : 🚧 en attente de validation par l'équipe.

> Les tâches sont décrites dans [`task-breakdown.md`](task-breakdown.md). La répartition et le planning (étape 4) viendront ensuite.

---

## 📖 Sommaire

- [Hypothèses d'estimation](#-hypothèses-destimation)
- [Estimations par tâche](#-estimations-par-tâche)
- [Totaux et marge](#-totaux-et-marge)

---

## 📐 Hypothèses d'estimation

- Les estimations sont en **heures de travail cumulées** (2 personnes × 1 h = 2 h).
- **Optimiste** : tout se passe bien du premier coup. **Réaliste** : inclut une relecture et une petite correction après la PR.
- Les estimations tiennent compte de l'usage de l'IA pour les squelettes et les premiers brouillons. Les décisions de fond restent prises par l'équipe.
- Le temps des réunions hebdomadaires est compté **uniquement** dans T03, pas dans les autres tâches.
- La marge d'environ **20 %** s'applique sur le total, pas tâche par tâche.

---

## 📋 Estimations par tâche

`●` = tâche sur le chemin critique.

### 🧭 Organisation et pilotage

| ID  | Tâche                              | Dép. | Prio      | Optimiste (h) | Réaliste (h) | Critique |
| --- | ---------------------------------- | ---- | --------- | ------------- | ------------ | -------- |
| T01 | Mise en place du dépôt et du suivi | —    | 🔴 Must   | 0,5           | 1            |          |
| T02 | Planning de l'équipe               | T01  | 🔴 Must   | 0,5           | 1            |          |
| T03 | Pilotage hebdo                     | —    | 🔴 Must   | 4             | 7            |          |
| T04 | Préparation des suivis pédago      | —    | 🟠 Should | 0,5           | 1            |          |
|     | **Sous-total**                     |      |           | **5,5**       | **10**       |          |

### 🔍 Phase 1 : Cadrage

| ID  | Tâche                                     | Dép.     | Prio    | Optimiste (h) | Réaliste (h) | Critique |
| --- | ----------------------------------------- | -------- | ------- | ------------- | ------------ | -------- |
| T05 | Hypothèses sur l'entreprise et le produit | —        | 🔴 Must | 1,5           | 2,5          |          |
| T06 | Veille marché et concurrence              | —        | 🔴 Must | 1,5           | 3            | ●        |
| T07 | Document de cadrage                       | T05, T06 | 🔴 Must | 2             | 3            | ●        |
| T08 | Plan de recherche                         | T07      | 🔴 Must | 1,5           | 2,5          | ●        |
| T09 | Feuille de route idéation et conception   | T07, T08 | 🔴 Must | 1,5           | 2,5          | ●        |
|     | **Sous-total**                            |          |         | **8**         | **13,5**     |          |

### 🗂️ Phase 2 : PMP

| ID  | Tâche                                   | Dép.                    | Prio      | Optimiste (h) | Réaliste (h) | Critique |
| --- | --------------------------------------- | ----------------------- | --------- | ------------- | ------------ | -------- |
| T10 | Gantt V1                                | T09                     | 🔴 Must   | 3             | 5            | ●        |
| T11 | Journal des révisions du Gantt          | T10                     | 🔴 Must   | 0,5           | 1            |          |
| T12 | Stratégie de production et de livraison | T05, T10                | 🔴 Must   | 1             | 2            |          |
| T13 | Liste des rôles du projet               | T10                     | 🔴 Must   | 1             | 1,5          |          |
| T14 | Fiches personas                         | T13                     | 🔴 Must   | 2             | 3,5          |          |
| T15 | Liste des ressources matérielles        | T10                     | 🔴 Must   | 1,5           | 2,5          | ●        |
| T16 | Recherche de fourchettes de prix        | T13, T15                | 🔴 Must   | 2             | 3,5          | ●        |
| T17 | Proposition de budget (Excel)           | T16                     | 🔴 Must   | 2             | 3            | ●        |
| T18 | Registre des risques                    | T07, T10                | 🔴 Must   | 1,5           | 2,5          |          |
| T19 | Imprévus simulés                        | T10, T18                | 🟠 Should | 0,5           | 1            |          |
| T20 | Gantt V2 et mise en cohérence           | T13, T15, T17, T18, T19 | 🔴 Must   | 2             | 3,5          | ●        |
| T21 | Document maître du PMP                  | T12, T20                | 🔴 Must   | 1,5           | 2,5          | ●        |
| T22 | Communication interne                   | T07, T10                | 🔴 Must   | 0,5           | 1            |          |
| T23 | Communication exécutive                 | T17, T18                | 🔴 Must   | 0,5           | 1            |          |
|     | **Sous-total**                          |                         |           | **19,5**      | **33,5**     |          |

### 🎤 Rendu

| ID  | Tâche                    | Dép.          | Prio      | Optimiste (h) | Réaliste (h) | Critique |
| --- | ------------------------ | ------------- | --------- | ------------- | ------------ | -------- |
| T24 | Journal des difficultés  | —             | 🟠 Should | 0,5           | 1            |          |
| T25 | README et index          | T21, T22, T23 | 🔴 Must   | 0,5           | 1            | ●        |
| T26 | Relecture croisée finale | T25           | 🔴 Must   | 1,5           | 3            | ●        |
| T27 | Exports PDF              | T14           | 🟠 Should | 0,5           | 1            |          |
| T28 | Slides de soutenance V1  | T17, T18, T20 | 🟠 Should | 2             | 3,5          |          |
|     | **Sous-total**           |               |           | **5**         | **9,5**      |          |

---

## 🧮 Totaux et marge

| Périmètre                 | Optimiste (h) | Réaliste (h) | Réaliste + 20 % (h) |
| ------------------------- | ------------- | ------------ | ------------------- |
| 🔴 Must uniquement        | 34            | 59           | **≈ 71**            |
| 🟠 Should                 | 4             | 7,5          | ≈ 9                 |
| **Total (Must + Should)** | **38**        | **66,5**     | **≈ 80**            |
