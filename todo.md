# 📝 To-do list

## ✏️ To-do

### 0. Organisation

- [ ] Prendre connaissance du Bootstrap (`docs/bootstrap.md`, `docs/smart_fridge-bootstrap.pdf`)
- [ ] Planifier le travail
- [ ] Répartir le travail entre les membres du groupe

### 1. Analyser le Gantt fourni (`docs/gantt.xlsx` — projet « Yes Connect »)

#### Explorer le document

- [ ] Comprendre la structure : WBS, tâche, lead, prédécesseur, start/end, days, % done, work days, estimated/real time, estimated/real costs, delta
- [ ] Comprendre la légende des barres : gris = Done, bleu = To do, jaune = start delayed, rouge = finish delayed
- [ ] Repérer le cadre : début le lun. 29/01/2018, 8 semaines affichées (jusqu'au 25/03), Project Lead « SNCB », 3 phases
  - `1` Design & Conception (lead P.M.), `2` App Dev (dev team), `3` Release (Comm° + dev team)
- [ ] Remarquer le coût unitaire implicite : 1 200 par jour (coût = temps × 1 200)

#### Relever les anomalies (à vérifier dans le fichier)

- [ ] **Budget** : 70 800 estimé → 154 800 réel (+84 000, ≈ +119 %)
  - Design : 36 000 → 67 200 (+31 200, ≈ +87 %)
  - App Dev : 19 200 → 39 600 (+20 400, ≈ +106 %)
  - Release : 15 600 → 48 000 (+32 400, ≈ +208 %), la phase qui dérape le plus
- [ ] **Temps estimé vs réel** (jours), tâches qui débordent (barres rouges) :
  - 1.1 User needs 5 → 8 · 1.5 UX/UI 5 → 11 · 1.6 User testing 5 → 14 · 1.7 User acceptance 5 → 12
  - 2.1 Functional specs 4 → 6 · 2.3 Architecture 3 → 12 · 2.4 Coding 5 → 7 · 2.5 Testing 3 → 7
  - 3.1 Internal comm 2 → 7 · 3.2 Social media 3 → 8 · 3.3 Press release 3 → 9 · 3.4 On-store publication 4 → 9 · 3.5 Support 1 → 7
  - Seules 1.2, 1.3, 1.4, 1.4.2 et 2.2 respectent l'estimation
- [ ] **Tâches non terminées** : UX/UI 40 %, User acceptance 50 %, Testing 60 %, User testing 75 %, Coding 80 %, Press release 80 %, Internal comm / Social media / Support 90 %
- [ ] **Démarrages retardés** (barres jaunes) : toute la phase App Dev (Functional specs, Technical specs, Coding, Testing), qui ne commence vraiment qu'autour du 27/02–05/03
- [ ] **Reprises tardives** : 2e bloc rouge vers le 12–16/03 sur Functional specs, Architecture, Coding et toutes les tâches Release → retravail en fin de projet
- [ ] **Ordonnancement incohérent** :
  - Colonne `PREDECESSOR` entièrement vide
  - Design sprint (01/02) et Prototype (02/02) démarrent avant la constitution de l'équipe (03/02) et avant le POC (08/02)
  - User testing (03/02) démarre avant l'UX/UI (05/02)
  - Architecture (14/02) est faite avant les Functional/Technical specs (27/02–04/03), d'où la refonte en mars
  - Testing démarre le même jour que le Coding (05/03)
  - Communication / press release (10–16/02) lancées avant même le début du développement
  - On-store publication et support (07/03) démarrent alors que coding et tests ne sont pas finis
- [ ] **Incohérences de données** : tâches planifiées sur des week-ends (DAYS ≠ WORK DAYS), Support : 3 work days mais 1 jour estimé, leads génériques (P.M., dev team, Comm°), `[Company Name]` non rempli
- [ ] **Portée du planning** : le Gantt s'arrête en semaine 8 alors que plusieurs tâches ne sont pas finies, et il n'y a aucun jalon ni marge prévus

#### Répondre aux questions du sujet

- [ ] Quels éléments m'indiquent que le projet ne s'est pas déroulé comme prévu ? (barres jaunes/rouges, % done < 100, real time > estimated, budget ×2,2)
- [ ] Quelles parties du projet étaient les plus sujettes aux imprévus ? (validation utilisateur 1.5–1.7, architecture, toute la Release)
- [ ] Ces imprévus ont-ils eu des conséquences sur d'autres parties du projet ? (design non validé → App Dev décalée → architecture refaite → Release décalée)
- [ ] Que pouvait faire l'équipe pour éviter de telles situations ? (dépendances explicites, specs avant archi, marges, jalons de validation, comm calée sur le produit, suivi régulier)
- [ ] Quelles sont les conséquences des différents retards ? (surcoût par phase, tâches inachevées, retravail)
- [ ] Quelles conséquences globales les retards ont-ils sur la suite du projet ? (+119 % de budget, publication sur store avec un produit non testé, communication désynchronisée)
- [ ] Ajouter nos propres questions / observations

#### Synthèse

- [ ] Rédiger les réponses dans `docs/gantt-analysis.md`
- [ ] En tirer une liste de « leçons apprises » à appliquer à notre propre Gantt

### 2. Construire notre diagramme de Gantt

#### Structure

- [ ] Choisir l'outil / le format (xlsx à partir du même template Vertex42, Google Sheets, Mermaid…) facile à mettre à jour et versionnable
- [ ] Reprendre les colonnes du template en **remplissant** `PREDECESSOR` et en nommant de vrais responsables
- [ ] Garder les colonnes estimated/real time et costs pour suivre les écarts
- [ ] Définir la date de début du projet, la date de livraison et des jalons (milestones)
- [ ] Garder la légende Done / To do / start delayed / finish delayed

#### Partie 1 — Préparation & cadrage du projet

- [ ] Lister les tâches de cadrage (analyse du besoin, étude de l'existant, constitution de l'équipe et rôles, choix techniques, outils, rituels d'équipe…)
- [ ] Ordonner : équipe → besoins → POC → design/prototype → tests utilisateurs → validation
- [ ] Estimer les durées (jours ouvrés uniquement) et assigner un responsable

#### Partie 2 — Construction & livraison du produit

- [ ] Lister les tâches de réalisation (specs fonctionnelles → specs techniques → architecture → développement → tests → déploiement → documentation → soutenance)
- [ ] Caler la communication / release **après** un jalon « produit testé »
- [ ] Estimer les durées, définir les dépendances et assigner un responsable
- [ ] Ajouter des marges de sécurité sur les tâches à risque (validation UX, architecture, tests)

#### Livraison de la version initiale

- [ ] Relire le Gantt en groupe (cohérence des dépendances, charge par personne, pas de tâche le week-end)
- [ ] Commit & push de la version initiale sur Git (ex. `docs/smart-fridge-gantt.xlsx`)
- [ ] Mettre à jour le `README.md` (contenu de `docs/`, lien vers le Gantt et l'analyse)

## 🔄 In progress

## ✅ Done
