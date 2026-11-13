# 🧩 Découpage du projet en tâches

> **Statut** : 🚧 en attente de validation par l'équipe.

> Les estimations sont dans [`estimation.md`](estimation.md). La répartition (étape 4) viendra ensuite.

---

## 📖 Sommaire

- [Conventions](#-conventions)
- [Organisation et pilotage](#-organisation-et-pilotage)
- [Phase 1 : Cadrage](#-phase-1--cadrage)
- [Phase 2 : PMP](#️-phase-2--pmp)
- [Rendu](#-rendu)

---

## 📐 Conventions

- **Source** : partie du sujet dont découle la tâche. Les pages renvoient à la numérotation du PDF (`docs/project/project.pdf`).
- **Priorités (MoSCoW)** :
  - **🔴 Must** : exigé explicitement par le sujet ;
  - **🟠 Should** : attendu à la soutenance ou nécessaire à la qualité ;
  - **🟡 Could** : bonus ;
  - **⚪ Won't** : hors des 4 semaines ou hors sujet.

---

## 🧭 Organisation et pilotage

| ID  | Tâche                              | Description                                                                                | Livrable / critère de fin                                         | Dép. | Prio      | Source                                            |
| --- | ---------------------------------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------- | ---- | --------- | ------------------------------------------------- |
| T01 | Mise en place du dépôt et du suivi | Arborescence `docs/` des livrables, conventions de branches, commits et PR, tâches saisies | Arborescence fusionnée sur `main`, toutes les tâches dans l'outil | —    | 🔴 Must   | p.4 (traçabilité par commits) + décision d'équipe |
| T02 | Planning de l'équipe               | Résultat des étapes d'estimation et de répartition, versionné                              | Fichier fusionné, mis à jour après chaque réunion                 | T01  | 🔴 Must   | Décision d'équipe                                 |
| T03 | Pilotage hebdo                     | 1 réunion par semaine (avancement, blocages, replanification) + relecture et fusion des PR | 4 réunions tenues, décisions notées dans l'outil de suivi         | —    | 🔴 Must   | Décision d'équipe                                 |
| T04 | Préparation des suivis pédago      | Point d'avancement et questions à poser                                                    | Liste prête la veille de chaque suivi                             | —    | 🟠 Should | Décision d'équipe                                 |

---

## 🔍 Phase 1 : Cadrage

| ID  | Tâche                                     | Description                                                                                                                                            | Livrable / critère de fin                                             | Dép.     | Prio    | Source                                                                |
| --- | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------- | -------- | ------- | --------------------------------------------------------------------- |
| T05 | Hypothèses sur l'entreprise et le produit | Taille de l'entreprise, marché cible, positionnement et fonctions clés, fabrication interne ou sous-traitée, horizon de commercialisation              | 1 page validée par les 3 membres en réunion                           | —        | 🔴 Must | p.3 (hypothèses initiales)                                            |
| T06 | Veille marché et concurrence              | Recherche documentaire sourcée : concurrents, prix publics, adoption, briques techniques, réglementation (CE, RGPD)                                    | Fichier de sources : ≥ 10 sources datées, résumées en 1 ligne chacune | —        | 🔴 Must | p.2 (faisabilité) + p.8 (« comment vous avez validé la faisabilité ») |
| T07 | Document de cadrage                       | Problème, hypothèses initiales, périmètre et hors périmètre, parties prenantes, critères du go/no-go                                                   | Document fusionné couvrant les 4 rubriques imposées                   | T05, T06 | 🔴 Must | p.3                                                                   |
| T08 | Plan de recherche                         | Étude de marché, recherche utilisateur, analyse concurrentielle et **faisabilité technique** : pour chacune, objectifs, méthodes et résultats attendus | 4 études décrites selon ces 3 rubriques                               | T07      | 🔴 Must | p.3                                                                   |
| T09 | Feuille de route idéation et conception   | Étapes, pourquoi, outils et méthodes, ordre, dépendances, ce qu'il faut valider en premier et pourquoi                                                 | Les 4 points « You must clearly describe » sont couverts              | T07, T08 | 🔴 Must | p.3                                                                   |

---

## 🗂️ Phase 2 : PMP

| ID  | Tâche                                   | Description                                                                                                                                                                                                       | Livrable / critère de fin                                          | Dép.                         | Prio      | Source                    |
| --- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ---------------------------- | --------- | ------------------------- |
| T10 | Gantt V1                                | À partir du modèle Excel : phases du cadrage à la commercialisation, tâches, dépendances, jalons go/no-go, activités parallèles, hypothèses de durée et de staffing                                               | `.xlsx` fusionné + export image + hypothèses listées               | T09                          | 🔴 Must   | p.4                       |
| T11 | Journal des révisions du Gantt          | Pour chaque version : date, changements, raison, lien vers l'export                                                                                                                                               | V1 consignée, puis complété à chaque version                       | T10                          | 🔴 Must   | p.4 (documents itératifs) |
| T12 | Stratégie de production et de livraison | Industrialisation, fabrication, certification, logistique, distribution, lancement                                                                                                                                | Section d'1 à 2 pages rattachée au PMP                             | T05, T10                     | 🔴 Must   | p.2 (mission)             |
| T13 | Liste des rôles du projet               | Analyse du Gantt V1 : 6 à 8 rôles du projet, phases où chacun intervient, tâches manquantes repérées                                                                                                              | Liste des rôles + liste des corrections à apporter au Gantt        | T10                          | 🔴 Must   | p.5                       |
| T14 | Fiches personas                         | Une persona par page : rôle, responsabilités, compétences, contribution                                                                                                                                           | 1 fiche par rôle de T13, toutes au même format                     | T13                          | 🔴 Must   | p.5                       |
| T15 | Liste des ressources matérielles        | Tableau des outils, technologies, équipements, services, formations et ateliers, avec quantités, disponibilité et délais                                                                                          | Tableau fusionné, chaque ressource à délai signalée pour le Gantt  | T10                          | 🔴 Must   | p.5                       |
| T16 | Recherche de fourchettes de prix        | Salaires par rôle, équipements, services, certification, prototypage, production, marketing                                                                                                                       | Chaque poste du budget a une fourchette sourcée                    | T13, T15                     | 🔴 Must   | p.6                       |
| T17 | Proposition de budget                   | Catégories, dépenses ponctuelles et récurrentes, fourchettes, total, justifications, échéances de financement liées aux go/no-go                                                                                  | `.xlsx` fusionné : total en fourchette, chaque ligne justifiée     | T16                          | 🔴 Must   | p.6                       |
| T18 | Registre des risques                    | ≥ 5 risques majeurs dont les 3 risques marché (adoption, prix, concurrence), avec probabilité, impact, atténuation et documents touchés                                                                           | ≥ 5 risques, les 3 risques marché couverts                         | T07, T10                     | 🔴 Must   | p.6 + p.8                 |
| T19 | Imprévus simulés                        | 1 ou 2 événements crédibles dans le projet (ex. pénurie de composants), avec impact et réponse                                                                                                                    | Événements décrits, impact chiffré (délai et coût)                 | T10, T18                     | 🟠 Should | p.8                       |
| T20 | Gantt V2 et mise en cohérence           | Intégrer tâches manquantes (T13), contraintes de ressources (T15), échéances budgétaires (T17), impacts des risques (T18), imprévus (T19) et préparation des communications ; mettre à jour les documents touchés | V2 fusionnée, journal complété, chaque changement relié à sa cause | T13, T15, T17, T18, T19      | 🔴 Must   | p.4 à 7                   |
| T21 | Document maître du PMP                  | Approche (PMBOK / PRINCE2), gouvernance, jalons de décision, pilotage, gestion des changements, renvoi vers chaque document                                                                                       | Document léger (≤ 4 pages), lien valide vers chaque livrable       | T12, T20 (squelette dès T07) | 🔴 Must   | p.4                       |
| T22 | Communication interne                   | Mail de lancement à l'équipe du projet : structure, objectifs, approche de management                                                                                                                             | ≤ 1 page, relu après T21                                           | T07, T10                     | 🔴 Must   | p.7                       |
| T23 | Communication exécutive                 | Note au board : montant demandé, justification, risques clés, go/no-go                                                                                                                                            | ≤ 1 page, mêmes chiffres que le budget                             | T17, T18                     | 🔴 Must   | p.7                       |

---

## 🎤 Rendu

| ID  | Tâche                                        | Description                                                                                                                    | Livrable / critère de fin                             | Dép.          | Prio         | Source                                |
| --- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------- | ------------- | ------------ | ------------------------------------- |
| T24 | Journal des difficultés                      | Tenu au fil de l'eau : difficulté méthodologique rencontrée et décision prise                                                  | ≥ 3 entrées au 13/12                                  | —             | 🟠 Should    | p.8 (écueils)                         |
| T25 | README et index                              | Sommaire des livrables avec liens et statuts, correction des liens morts                                                       | Tous les liens fonctionnent                           | T21, T22, T23 | 🔴 Must      | p.8 (« structured to allow anyone… ») |
| T26 | Relecture croisée finale                     | Orthographe, mêmes chiffres partout, liens                                                                                     | Liste de contrôle cochée, PR de corrections fusionnée | T25           | 🔴 Must      | p.8                                   |
| T27 | Exports PDF                                  | Personas (une par page) + autres documents si besoin                                                                           | PDF dans le dépôt                                     | T14           | 🟠 Should    | p.5                                   |
| T28 | Slides de soutenance V1                      | Faisabilité, choix de ressources et de budget, risques marché, adaptations du planning, difficultés ; répartition de la parole | Deck V1 avant le 13/12, une partie par membre         | T17, T18, T20 | 🟠 Should    | p.8                                   |
| —   | Répétition, Gantt V3, réalisation des études | —                                                                                                                              | —                                                     | —             | **⚪ Won't** | Hors des 4 semaines ou hors sujet     |
