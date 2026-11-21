# 🧊 Document de cadrage

> **Statut** : 📝 squelette (T07). Sections d'Antonin prérédigées, sections de Xavier à rédiger (échéance ven
> 20/11), version finale le dim 22/11.

Référence commune pour toutes les parties prenantes. Ce document définit **le cadre dans lequel un produit
pertinent, faisable et bien structuré pourrait être développé**. Il ne conçoit pas le produit et ne présente
aucun résultat d'étude.

## 📖 Sommaire

- [Problème](#-problème)
- [Hypothèses initiales](#-hypothèses-initiales)
- [Périmètre et hors périmètre](#-périmètre-et-hors-périmètre)
- [Parties prenantes](#-parties-prenantes)
- [Critères du go/no-go](#-critères-du-gono-go)

---

## ❓ Problème

> ✍️ Antonin

Une entreprise d'électroménager de taille moyenne voit ses marges sur les réfrigérateurs classiques se réduire
: la concurrence est forte et l'innovation stagne. Le conseil de direction envisage le **réfrigérateur
intelligent connecté** comme prochain levier de croissance, mais ne veut pas engager des millions sans réponse
à trois questions :

| Question                                     | Ce qu'il faut établir                                                                                        |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Existe-t-il un **réel besoin utilisateur** ? | Un problème vécu par des utilisateurs, assez fort pour justifier l'achat d'un produit plus cher.             |
| Le projet a-t-il du **sens business** ?      | Un prix, un volume et une marge compatibles avec l'investissement.                                           |
| Est-il **faisable** ?                        | Techniquement (briques, intégration, sécurité) et opérationnellement (production, certification, livraison). |

L'entreprise n'a pas de méthode claire pour initier un projet au-delà de l'analyse de marché. Le problème à
résoudre ici est donc double : **structurer la phase d'idéation et de conception**, et **fournir au board les
éléments d'une décision go/no-go**.

## 🧭 Hypothèses initiales

> ✍️ Antonin · détail et justifications dans [`hypotheses.md`](hypotheses.md) (T05)

| Thème                        | Hypothèse retenue                                 |
| ---------------------------- | ------------------------------------------------- |
| Taille de l'entreprise       | _à reprendre de `hypotheses.md` après validation_ |
| Marché cible                 | _idem_                                            |
| Positionnement et fonctions  | _idem_                                            |
| Fabrication                  | _idem_                                            |
| Horizon de commercialisation | _idem_                                            |

Ces hypothèses sont **initiales** : elles seront confirmées, corrigées ou rejetées par les études du
[plan de recherche](plan-de-recherche.md) (T08). Tout changement est tracé dans l'historique des commits.

## 🔲 Périmètre et hors périmètre

> ✍️ Xavier (ven 20/11)

**Dans le périmètre**

- _à rédiger_

**Hors périmètre**

- _à rédiger_
- Rappel imposé par le sujet : on **définit** les actions et on étudie la faisabilité, on ne les **exécute**
  pas (pas de conception détaillée, de prototype ni d'études réalisées).

## 👥 Parties prenantes

> ✍️ Xavier (ven 20/11)

| Partie prenante | Rôle dans le projet | Intérêt / attente | Influence |
| --------------- | ------------------- | ----------------- | --------- |
| _à rédiger_     |                     |                   |           |

## 🚦 Critères du go/no-go

> ✍️ Antonin

Le go/no-go est une décision **du board**, éclairée par ce dossier. Chaque critère correspond à l'une des
trois questions du [problème](#-problème). Les seuils sont des **propositions à calibrer** une fois la veille
de marché (T06) terminée.

| Axe                        | Critère de « go »                                                                                                    | Étude qui l'éclaire (T08)     |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| Besoin utilisateur         | Un problème récurrent est confirmé et la fonction clé est jugée utile par une large part des utilisateurs interrogés | Recherche utilisateur         |
| Sens business              | Marge positive au prix visé, volume de ventes réaliste, retour sur investissement dans l'horizon fixé                | Étude de marché + concurrence |
| Faisabilité technique      | Les briques clés existent et sont intégrables sans risque bloquant (sécurité, fiabilité)                             | Faisabilité technique         |
| Faisabilité opérationnelle | Certification (CE, RGPD) et production réalisables dans les délais                                                   | Faisabilité technique + T12   |

**Règle de décision** (à valider en réunion) : **go** si les quatre axes sont satisfaits ; **no-go** si un
seul est clairement négatif ; **go conditionnel** (avec plan d'atténuation) dans les autres cas.

Les points de décision se retrouvent comme **jalons du Gantt** (T10).
