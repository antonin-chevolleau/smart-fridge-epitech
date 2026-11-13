# 🧊 Smart Fridge — Initier et planifier un projet

> Source : sujet Epitech _Smart Fridge_ (v1.3), traduit et condensé.

---

## 📖 Sommaire

- [Contexte et mission](#-contexte-et-mission)
- [Récapitulatif des livrables](#-récapitulatif-des-livrables)
- [Phase 1 — Cadrage](#-phase-1--cadrage)
  - [Livrables](#-livrables)
- [Phase 2 — Plan de management de projet (PMP)](#️-phase-2--plan-de-management-de-projet-pmp)
  - [Temps — diagramme de Gantt](#️-temps--diagramme-de-gantt)
  - [Ressources humaines — profils et compétences](#-ressources-humaines--profils-et-compétences)
  - [Ressources matérielles — liste de ressources](#-ressources-matérielles--liste-de-ressources)
  - [Coûts — proposition de budget](#-coûts--proposition-de-budget)
  - [Risques — registre des risques](#️-risques--registre-des-risques)
  - [Communication](#-communication)
- [Règle transverse : tout se reflète dans le Gantt](#-règle-transverse--tout-se-reflète-dans-le-gantt)
- [Rendu — revue de groupe](#-rendu--revue-de-groupe)
- [Glossaire](#-glossaire)

---

## 🎯 Contexte et mission

Les objets connectés (thermostats, assistants vocaux, aspirateurs, serrures…) automatisent de plus en plus la maison. Une entreprise d'électroménager de taille moyenne voit ses marges sur les réfrigérateurs classiques se réduire face à une concurrence forte et une innovation en panne. Le conseil de direction envisage le **réfrigérateur intelligent connecté** comme prochain levier de croissance.

Avant d'investir des millions, il veut savoir :

- s'il existe un **réel besoin utilisateur**
- si le projet a du **sens business**
- s'il est **faisable** techniquement et opérationnellement

En tant qu'expert en transformation numérique, notre rôle est de **cadrer**, **analyser** et **structurer** le projet pour éclairer une décision (_go/no-go_), de l'exploration initiale jusqu'à la préparation à la commercialisation.

> ⚠️ On **définit** les actions et on étudie faisabilité et viabilité — on ne les **exécute** pas.

**Responsabilités** :

- cadrer le projet
- présenter une stratégie de production et de livraison
- étudier les ressources nécessaires
- proposer un budget
- maîtriser les risques
- identifier les compétences et profils pertinents
- communiquer sur le projet

---

## 📋 Récapitulatif des livrables

| #   | Livrable                        | Contrainte clé                                                                     |
| --- | ------------------------------- | ---------------------------------------------------------------------------------- |
| 1   | Document de cadrage             | problème, hypothèses, périmètre, hors périmètre                                    |
| 2   | Plan de recherche               | objectifs, méthodes, résultats attendus                                            |
| 3   | Feuille de route de haut niveau | étapes, séquence, dépendances, ce qui doit être validé en premier                  |
| 4   | PMP — document maître           | léger, référence les documents spécialisés, mis à jour et traçable via les commits |
| 5   | Diagramme de Gantt              | phases, tâches, dépendances, jalons de décision, parallélisme                      |
| 6   | Profils et compétences          | une persona par page                                                               |
| 7   | Liste de ressources             | tableau : quantités et disponibilité si pertinent                                  |
| 8   | Proposition de budget           | catégories, ponctuel vs récurrent, fourchettes de prix réalistes                   |
| 9   | Registre des risques            | ≥ 5 risques majeurs : probabilité, impact, atténuation                             |
| 10  | Communication interne           | pour l'équipe projet                                                               |
| 11  | Communication exécutive         | pour un membre du board, centrée sur la demande de budget                          |
| 12  | Revue de groupe (rendu final)   | faisabilité, justifications, risques marché, adaptations, écueils                  |

---

## 🧭 Phase 1 — Cadrage

Le but n'est **pas** de concevoir ou valider le produit, mais de définir les conditions dans lesquelles un produit pertinent, faisable et bien structuré pourrait être développé ensuite. L'entreprise n'a pas de méthode claire pour initier un projet au-delà de l'analyse de marché : il faut donc **structurer la phase d'idéation et de conception**.

Pour chaque étape de cette phase, décrire :

- **quelles** étapes sont nécessaires
- **pourquoi** chacune compte et ce qu'elle doit produire
- **avec quels outils / méthodes** courants la réaliser
- **dans quel ordre** elles s'enchaînent et comment elles dépendent les unes des autres

> 🎯 Objectif : réduire l'incertitude, aligner les parties prenantes et préparer une décision éclairée avant d'engager temps, budget et ressources.

> ⚠️ Expliquer le _pourquoi, comment et quoi_ avant tout développement

### 📦 Livrables

Un ensemble cohérent de documents qui définissent **l'approche, pas les résultats** :

- **Document de cadrage** — espace du problème, hypothèses initiales, périmètre et hors périmètre. Référence commune pour toutes les parties prenantes.
- **Plan de recherche** — analyses à mener plus tard (étude de marché, recherche utilisateur, analyse concurrentielle) avec objectifs, méthodes et résultats attendus, sans les exécuter.
- **Feuille de route de haut niveau** — étapes clés de l'idéation et de la conception, séquence et dépendances. Met l'accent sur _ce qui doit être clarifié_ et sur ce qu'il faut valider en premier, et pourquoi.

> 💡 Ces livrables doivent montrer la capacité à anticiper, à structurer l'ambiguïté et à poser des bases solides.

---

## 🗂️ Phase 2 — Plan de management de projet (PMP)

Structurer le chemin vers la livraison du produit : comment le projet serait **organisé, gouverné et contrôlé** s'il était lancé.

- Un **document maître léger** décrit l'approche globale et référence des **documents de support spécialisés** ; l'ensemble doit rester cohérent.
- Tous les documents sont **itératifs** : ils sont mis à jour à chaque nouvel élément, contrainte ou lacune, et chaque modification doit être facilement identifiable dans les **commits** du dépôt.

> ℹ️ S'inspirer de référentiels éprouvés (PMBOK, PRINCE2).

### ⏱️ Temps — diagramme de Gantt

Planifier le projet, du cadrage à la livraison, en passant par la mise en œuvre :

- phases, tâches et dépendances ;
- hypothèses sur l'enchaînement, la durée et le _staffing_ ;
- points de décision, activités parallèles et liens logiques.

Une **première version** expose le raisonnement et les hypothèses initiales, puis elle est **révisée** au fil du projet.

### 👥 Ressources humaines — profils et compétences

À partir du cadrage et du planning, analyser le travail pour identifier les **compétences et profils** nécessaires (rôles, compétences, état d'esprit, au bon moment).

- Format : un ensemble de **personas, une par page**.
- Chaque persona décrit : le rôle, ses responsabilités principales, ses compétences clés et sa contribution au projet.

> ℹ️ Cette analyse sert aussi de test de cohérence : si elle révèle des tâches manquantes ou sous-estimées, mettre à jour le plan et le Gantt.

### 🧰 Ressources matérielles — liste de ressources

Anticiper tout ce qui est nécessaire au-delà des personnes : outils, technologies, équipements, services, formations, ateliers, autres supports.

- Raisonner de façon réaliste sur la **disponibilité** et les **contraintes** : certaines ressources introduisent des délais ou des dépendances.
- Format : un **tableau** listant les ressources, avec quantités et hypothèses de disponibilité quand c'est pertinent.

### 💰 Coûts — proposition de budget

Traduire compétences et ressources en **projection budgétaire** :

- fourchettes de prix réalistes et recherchées
- coûts organisés par catégories
- distinction dépenses **ponctuelles** / **récurrentes**
- choix justifiés, réalisme économique

> ℹ️ Ce n'est pas un exercice de comptabilité et il n'y a pas de solution unique : la **cohérence et la pertinence** sont évaluées, pas l'exactitude.

### ⚠️ Risques — registre des risques

Identifier **au moins 5 risques majeurs**, chacun avec :

- sa **probabilité**
- son **impact**
- une **stratégie d'atténuation**

> ℹ️ La pertinence prime sur l'exhaustivité : viser les risques les plus critiques.

Si un risque touche le planning, le budget, les ressources ou les compétences, mettre à jour les documents correspondants.

### 📣 Communication

Expliquer le projet, ses contraintes et ses besoins de façon claire et professionnelle, à deux publics :

- **Communication interne** — pour l'équipe projet : structure, objectifs, approche de management
- **Communication exécutive** — pour un membre du _board_ : demande de budget et sa justification

> ℹ️ Adapter le message au public : attentes, niveau d'implication et expertise technique différents.

---

## 🔁 Règle transverse : tout se reflète dans le Gantt

Le Gantt doit être mis à jour pour intégrer :

- les tâches manquantes révélées par l'analyse des compétences
- les contraintes et dépendances liées aux ressources
- les échéances et contraintes budgétaires
- les impacts des risques sur le planning
- la préparation des communications

---

## 🎤 Rendu — revue de groupe

Le rendu est une **revue des documents, en groupe**. Il faut :

- présenter comment la **faisabilité technique** a été validée
- justifier les choix, en particulier **ressources et budget**
- expliquer comment les **risques marché** (adoption, prix, concurrence) sont atténués
- montrer comment le **planning** et les livrables ont été adaptés face aux imprévus
- expliquer les **écueils** rencontrés et leur traitement

> ⚠️ Le rendu doit être structuré pour que n'importe qui comprenne facilement le projet.

---

## 📚 Glossaire

| Terme                           | Sens                                                                    |
| ------------------------------- | ----------------------------------------------------------------------- |
| _go/no-go_                      | décision de lancer ou non le projet                                     |
| _problem space_                 | le besoin / la problématique, indépendamment de la solution             |
| PMP (_Project Management Plan_) | plan de management de projet                                            |
| PMBOK                           | _Project Management Body of Knowledge_ — référentiel du PMI             |
| PRINCE2                         | _PRojects IN Controlled Environments_ — méthode de management de projet |
| _staffing_                      | affectation des personnes aux tâches                                    |
| _persona_                       | fiche représentant un profil type (ici : un rôle du projet)             |
| _one-off_ / _recurring_         | dépense ponctuelle / récurrente                                         |
| _risk register_                 | registre des risques                                                    |
| _board member_                  | membre du conseil d'administration                                      |
