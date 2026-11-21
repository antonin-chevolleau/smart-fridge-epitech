# 🧭 Hypothèses sur l'entreprise et le produit

> **Statut** : 📝 brouillon pour la réunion du mar 17/11 (T05). Chaque ligne est une **proposition** à
> valider, modifier ou rejeter par les 3 membres.

Ces hypothèses fixent le cadre commun du cadrage (T07), du Gantt (T10), du budget (T17) et de la stratégie de
production (T12). Le sujet ne les donne pas : sans elles, chacun estimerait sur une base différente. Elles
sont révisables, mais tout changement est consigné dans l'historique des commits.

---

## 🏭 1. Taille de l'entreprise

|                 |                                                                                                                                                   |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hypothèse**   | Entreprise d'électroménager de taille moyenne : ≈ 1 500 salariés, ≈ 400 M€ de chiffre d'affaires, usines en Europe.                               |
| **Pourquoi**    | Le sujet dit « taille moyenne » et parle d'investir « des millions » : assez grande pour financer un produit, trop petite pour tout internaliser. |
| **Impacte**     | Budget (T17) : capacité d'investissement. Rôles (T13) : équipes déjà présentes (R&D, achats, marketing).                                          |
| **Alternative** | ≈ 300 salariés : moins d'équipes internes, plus de sous-traitance et de recrutement.                                                              |

## 🎯 2. Marché cible

|                 |                                                                                                                                          |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| **Hypothèse**   | Foyers urbains de 2 à 4 personnes en Europe de l'Ouest (France d'abord), équipés d'un smartphone, qui font leurs courses chaque semaine. |
| **Pourquoi**    | Premier marché accessible à l'entreprise, avec une réglementation unique (CE, RGPD) à étudier.                                           |
| **Impacte**     | Étude de marché et recherche utilisateur (T08), certification (T12), prix (T16).                                                         |
| **Alternative** | Cible plus étroite : seniors ou familles nombreuses. Plus précis, mais marché plus petit.                                                |

## 🏷️ 3. Positionnement et fonctions clés

|               |                                                                                                                                                                                 |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hypothèse** | Positionnement milieu-haut de gamme, « premium accessible » : un réfrigérateur d'abord performant, ensuite connecté.                                                            |
| **Fonctions** | Inventaire du contenu (caméra intérieure), alertes de péremption, liste de courses, suggestions de recettes, suivi de la température et de la consommation, application mobile. |
| **Pourquoi**  | Répond au besoin supposé (moins de gaspillage, gain de temps) et se différencie de la concurrence sans viser le très haut de gamme.                                             |
| **Impacte**   | Faisabilité technique (T08), ressources (T15), coût de revient et prix (T16, T17).                                                                                              |
| **À valider** | Ces fonctions sont une **hypothèse de besoin** : c'est la recherche utilisateur (T08) qui doit les confirmer ou les écarter.                                                    |

## 🔧 4. Fabrication : interne ou sous-traitée

|                 |                                                                                                                                                                                                                                    |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hypothèse**   | Hybride : le réfrigérateur est assemblé dans une usine de l'entreprise ; l'électronique (capteurs, caméra, connectivité) vient d'un sous-traitant ; le logiciel et l'application sont développés en interne ou par un prestataire. |
| **Pourquoi**    | L'entreprise maîtrise le froid et l'assemblage, mais pas l'électronique embarquée ni le logiciel connecté.                                                                                                                         |
| **Impacte**     | Stratégie de production (T12), délais d'approvisionnement (T15), risques fournisseurs (T18, T19).                                                                                                                                  |
| **Alternative** | Tout sous-traité à un fabricant (ODM) : plus rapide et moins cher au départ, moins de contrôle sur la qualité et la marge.                                                                                                         |

## 📅 5. Horizon de commercialisation

|                 |                                                                                                                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Hypothèse**   | Lancement commercial ≈ 30 mois après la décision de départ : idéation et conception ≈ 9 mois, prototypage et certification ≈ 9 mois, industrialisation ≈ 9 mois, lancement ≈ 3 mois. |
| **Pourquoi**    | Ordre de grandeur courant pour un appareil électroménager connecté qui doit être certifié et industrialisé.                                                                          |
| **Impacte**     | Gantt (T10) : durée des phases ; budget (T17) : étalement des dépenses ; jalons go/no-go.                                                                                            |
| **Alternative** | 18 mois (calendrier agressif) : suppose de réutiliser une plateforme existante et augmente le risque.                                                                                |

---

## ❓ Points à trancher en réunion

- [ ] Taille de l'entreprise : 1 500 salariés ou autre ?
- [ ] Marché : France seule ou Europe de l'Ouest dès le lancement ?
- [ ] Fonctions clés : lesquelles sont indispensables au lancement, lesquelles viennent plus tard ?
- [ ] Fabrication : hybride ou tout sous-traité ?
- [ ] Horizon : 30 mois ou autre ?

## ✅ Décisions

À remplir en réunion : une ligne par hypothèse retenue, avec la date et les 3 validations.
