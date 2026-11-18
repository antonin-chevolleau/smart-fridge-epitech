# Tâches de TK

Ce fichier regroupe les tâches attribuées à TK dans le planning de l’équipe, ainsi que ses contributions aux tâches collectives.

Sources : [planning](planning.md), [découpage des tâches](task-breakdown.md), [estimations](estimation.md).

> Le planning source est en attente de validation par l’équipe. Les dates ci-dessous sont les échéances de fusion sur `main`, en 2026. Les cases permettent de suivre l’avancement, sans présumer que les tâches sont déjà terminées.

## Tâches dont TK est responsable

### S1 — 16 au 22 novembre : hypothèses et veille

- [ ] **T05 — Hypothèses sur l’entreprise et le produit** — mardi 17/11
  - Préparer et rédiger une page : taille de l’entreprise, marché cible, positionnement, fonctions clés, fabrication interne ou sous-traitée et horizon de commercialisation.
  - Faire valider les hypothèses par les trois membres en réunion.
  - **Livrable :** une page validée par l’équipe.
  - **Avec :** Antonin et Xavier.
  - **Dépendances :** aucune.

- [ ] **T06 — Veille marché et concurrence** — mercredi 18/11
  - Rechercher des informations sur les concurrents, prix publics, adoption, briques techniques et réglementation (CE, RGPD).
  - **Livrable :** fichier contenant au moins 10 sources datées, chacune résumée en une ligne.
  - **Dépendances :** aucune ; cette tâche alimente le cadrage T07.

### S2 — 23 au 29 novembre : plan de recherche

- [ ] **T08 — Plan de recherche** — mardi 24/11
  - Décrire quatre études : marché, utilisateurs, concurrence et faisabilité technique.
  - Préciser pour chacune les objectifs, les méthodes et les résultats attendus.
  - **Livrable :** plan présentant les quatre études selon ces trois rubriques, sans les exécuter.
  - **Dépendance :** T07, document de cadrage.

### S3 — 30 novembre au 6 décembre : ressources, prix et budget

- [ ] **T15 — Liste des ressources matérielles** — mardi 01/12
  - Recenser outils, technologies, équipements, services, formations et ateliers.
  - Préciser les quantités, disponibilités et délais pertinents.
  - **Livrable :** tableau fusionné ; chaque ressource introduisant un délai est signalée pour mise à jour du Gantt.
  - **Dépendance :** T10, Gantt V1.

- [ ] **T16 — Recherche de fourchettes de prix** — jeudi 03/12
  - Rechercher les coûts des salaires par rôle, équipements, services, certification, prototypage, production et marketing.
  - **Livrable :** une fourchette sourcée pour chaque poste du budget.
  - **Avec :** Antonin.
  - **Dépendances :** T13, liste des rôles ; T15, ressources matérielles.

- [ ] **T19 — Imprévus simulés** — vendredi 04/12
  - Décrire un ou deux événements crédibles, par exemple une pénurie de composants.
  - Définir leur impact et la réponse envisagée.
  - **Livrable :** événements documentés avec impacts chiffrés en délai et en coût.
  - **Dépendances :** T10, Gantt V1 ; T18, registre des risques.
  - **Priorité :** Should, ajustable si nécessaire.

- [ ] **T17 — Proposition de budget (Excel)** — dimanche 06/12
  - Organiser les coûts par catégorie, en distinguant dépenses ponctuelles et récurrentes.
  - Présenter les fourchettes, le total, les justifications et les échéances de financement liées aux décisions go/no-go.
  - **Livrable :** fichier `.xlsx` fusionné, avec total en fourchette et justification de chaque ligne.
  - **Avec :** Antonin.
  - **Dépendance :** T16, recherche de prix.

### S4 — 7 au 13 décembre : stratégie et communication

- [ ] **T23 — Communication exécutive** — lundi 07/12
  - Rédiger une note au conseil d’administration : montant demandé, justification, risques clés et décision go/no-go.
  - **Livrable :** une page maximum, avec les mêmes chiffres que le budget.
  - **Dépendances :** T17, budget ; T18, registre des risques.

- [ ] **T12 — Stratégie de production et de livraison** — mardi 08/12
  - Décrire industrialisation, fabrication, certification, logistique, distribution et lancement.
  - **Livrable :** section d’une à deux pages rattachée au PMP.
  - **Dépendances :** T05, hypothèses ; T10, Gantt V1.

- [ ] **T27 — Exports PDF** — vendredi 11/12
  - Exporter les personas en respectant une page par persona, ainsi que les autres documents si nécessaire.
  - **Livrable :** PDF présents dans le dépôt.
  - **Dépendance :** T14, fiches personas.
  - **Priorité :** Should, ajustable si nécessaire.

## Contributions aux tâches collectives

- [ ] **T03 — Pilotage hebdomadaire** — S1 à S4
  - Participer aux réunions d’avancement, signaler les blocages et contribuer aux décisions de replanification.
  - **Responsable :** Antonin ; participation de tous.

- [ ] **T10 — Gantt V1** — dimanche 29/11
  - Préparer les phases d’industrialisation et de commercialisation.
  - Contribuer aux tâches, dépendances, jalons, activités parallèles et hypothèses de durée et de staffing.
  - **Livrable collectif :** fichier `.xlsx`, export image et hypothèses listées.
  - **Responsable :** Antonin.
  - **Dépendance :** T09, feuille de route.

- [ ] **T20 — Gantt V2 et mise en cohérence** — contribution TK : mardi 08/12
  - Intégrer les contraintes des ressources, les échéances budgétaires, les risques et les imprévus.
  - Mettre à jour les documents concernés et vérifier la cohérence avec les travaux de TK.
  - **Livrable collectif :** Gantt V2 fusionné, journal complété et changements reliés à leurs causes.
  - **Responsable :** Antonin ; contribution de tous.
  - **Dépendances :** T13, T15, T17, T18 et T19.
  - **Jalon collectif :** Gantt V2 et PMP fusionnés le mercredi 09/12.

- [ ] **T24 — Journal des difficultés** — S1 à S4
  - Transmettre les difficultés méthodologiques rencontrées et les décisions prises au fil du travail.
  - **Livrable collectif :** au moins trois entrées au 13/12.
  - **Responsable :** Xavier ; contribution de tous.
  - **Priorité :** Should.

- [ ] **T26 — Relecture croisée finale** — vendredi 11/12
  - Vérifier la cohérence des chiffres et des liens avec Antonin.
  - **Livrable collectif :** liste de contrôle cochée et corrections fusionnées.
  - **Responsable :** Antonin ; contribution de tous.
  - **Dépendance :** T25, README et index.

- [ ] **T28 — Slides de soutenance V1** — vendredi 11/12
  - Fournir le contenu de sa partie de la présentation.
  - Contribuer à l’explication de la faisabilité, des choix de ressources et de budget, des risques marché, des adaptations du planning et des difficultés.
  - **Livrable collectif :** deck V1 avant le 13/12, avec une partie par membre ; assemblage par Xavier.
  - **Dépendances :** T17, T18 et T20.
  - **Priorité :** Should.

## Échéances finales

- **Vendredi 11/12 :** documents relus et dépôt gelé.
- **Samedi 12/12 et dimanche 13/12 :** marge, aucune tâche prévue.
- **Dimanche 13/12 :** rendu GitHub.
- **Semaine du 14/12 :** soutenance, date à confirmer.

> Toutes les tâches sont Must sauf celles explicitement marquées Should. Les estimations du document source sont des charges cumulées pour l’équipe, pas des charges individuelles de TK.
