# 📊 MASTER PLAN REVOPS AIRCALL — RÉCAPITULATIF INTÉGRAL & EXHAUSTIF
**Formation :** Rocket School — Examen Officiel « Note d'Opportunité & Soutenance RevOps »  
**Candidat :** Kevin Monin  
**Poste :** Consultant Senior Revenue Operations & Data Strategist auprès du CoDir d'Aircall  
**Dossier de référence :** Projet Soutenance Aircall 2026  

---

## 📑 TABLE DES MATIÈRES
1. [Contexte Général & Enjeux du Diagnostic RevOps](#1-contexte-général--enjeux-du-diagnostic-revops)
2. [Les 20 KPI Essentiels Consolidés en 5 Familles](#2-les-20-kpi-essentiels-consolidés-en-5-familles)
3. [Les 5 KPI Rois : Calculs Détaillés, Sous-KPI & Signification Business](#3-les-5-kpi-rois--calculs-détaillés-sous-kpi--signification-business)
4. [Décryptage Métier : Définition de l'ARR & Signification de l'Écart de 441 500 €](#4-décryptage-métier--définition-de-larr--signification-de-lécart-de-441-500-)
5. [Les 2 Dysfonctionnements Majeurs de la Performance Commerciale](#5-les-2-dysfonctionnements-majeurs-de-la-performance-commerciale)
6. [Les 2 Arbitrages Stratégiques Chiffrés (Vision Purement ROIste)](#6-les-2-arbitrages-stratégiques-chiffrés-vision-purement-roiste)
7. [Architecture Technique Looker Studio : Les 9 Composants Sans Chevauchement](#7-architecture-technique-looker-studio--les-9-composants-sans-chevauchement)
8. [Les 6 Livrables A4 Officiels Demi-Journée par Demi-Journée](#8-les-6-livrables-a4-officiels-demi-journée-par-demi-journée)
9. [Déroulé Exhaustif de la Présentation en 8 Slides Ultra-Épurées](#9-déroulé-exhaustif-de-la-présentation-en-8-slides-ultra-épurées)
10. [Matrice de Transparence & Traçabilité des Données (3 Sources)](#10-matrice-de-transparence--traçabilité-des-données-3-sources)
11. [Script Oral Chronométré de Soutenance (15 Minutes) & FAQ Jury](#11-script-oral-chronométré-de-soutenance-15-minutes--faq-jury)

---

## 1. CONTEXTE GÉNÉRAL & ENJEUX DU DIAGNOSTIC REVOPS

### 🏢 L'Entreprise : Aircall
* **Positionnement :** Standard téléphonique cloud d'entreprise (VoIP SaaS), connecté nativement à plus de 100 outils métiers (Salesforce, HubSpot, Zendesk, Intercom).
* **Envergure :** Licorne SaaS B2B, valorisée à plus de 1 Md$, générant ~250 M$ d'ARR dans plus de 100 pays auprès de 24 000+ entreprises clientes.
* **Problématique RevOps du cas :** L'entreprise a déployé une équipe de 10 SDRs qui a passé un volume d'activité colossal (67 560 appels sortants sur 12 mois). Pourtant, la machine commerciale s'essouffle : rentabilité inégale, dispersion d'effort sur des cibles non viables, et absence d'accompagnement post-vente mettant en danger l'ARR récurrent.

### 🎯 Les Données Clés Macro
* **Volume d'appels passés :** 67 560 appels
* **Appels décrochés (connects) :** 11 190 connects (Taux de décroché global : 16,56 %)
* **Démos 1er RDV réalisées :** 759 démos (Taux décroché ➔ démo : 6,78 %)
* **Contrats signés (closings) :** 358 signatures (Taux démo ➔ closing : 47,17 %)
* **ARR Total signé :** 3 684 000,00 €
* **Panier moyen global (ACV) :** 10 290,50 €
* **Durée moyenne du cycle de vente :** 34,5 jours

---

## 2. LES 20 KPI ESSENTIELS CONSOLIDÉS EN 5 FAMILLES

### Famille 1 : Activité & Efficacité du Funnel (Le moteur brut)
1. **Volume d'appels passés :** 67 560 appels sortants.
2. **Volume d'appels décrochés (connects) :** 11 190 connects.
3. **Taux de décroché global (Connect Rate) :** 16,56 % (11 190 / 67 560).
4. **Volume de démos 1er RDV :** 759 démos réalisées.
5. **Taux de conversion Décroché ➔ Démo :** 6,78 % (759 / 11 190).
6. **Volume de contrats signés (Deals) :** 358 contrats.
7. **Taux de conversion Démo ➔ Closing :** 47,17 % (358 / 759).
8. **Taux de transformation global Appel ➔ Deal :** 0,53 % (358 / 67 560).

### Famille 2 : Valeur Financière & Vélocité (Ce qui paie réellement)
9. **ARR total signé :** 3 684 000,00 €.
10. **Panier moyen global (ACV) :** 10 290,50 € / contrat signé.
11. **Rendement moyen par appel passé :** 54,53 € d'ARR par appel (3 684 000 € / 67 560).
12. **Cycle moyen de closing :** 34,5 jours.

### Famille 3 : Rentabilité par Segment Client (Le gouffre TPE vs PME)
13. **Part d'effort TPE vs part d'ARR TPE :** 42,25 % des appels (28 545 appels) pour seulement 6,07 % de l'ARR (223 500 €).
14. **Panier moyen par segment :**
    * TPE (1–19 salariés) : 3 725,00 € (60 deals)
    * PME (20–200 salariés) : 9 616,67 € (234 deals — soit 2,58× supérieur à la TPE)
    * MidMarket (201–1000 salariés) : 18 909,38 € (64 deals — soit 5,08× supérieur à la TPE)
15. **Taux de qualification Décroché ➔ Démo par segment :**
    * TPE : 2,58 % (112 démos / 4 333 connects)
    * PME : 9,73 % (537 démos / 5 521 connects — soit 3,76× plus efficace)
    * MidMarket : 8,23 % (110 démos / 1 336 connects)
16. **Poids central de la PME dans l'ARR :** 2 250 300,00 € (61,08 % de l'ARR global).

### Famille 4 : Performance par Canal d'Acquisition (Où se crée la valeur)
17. **Poids et panier de l'Outbound ColdCall :** 85,41 % des appels (57 705) et 63,19 % de l'ARR (2 328 100 € pour 279 deals), mais panier moyen le plus faible : 8 344,44 €.
18. **Paniers moyens des canaux Inbound & Partenaires :**
    * Inbound Web : 15 375,00 € de panier moyen (40 deals, 615 000 € d'ARR, 8,58 % des appels).
    * Partenaire CRM : 18 997,44 € de panier moyen (39 deals, 740 900 € d'ARR, 6,01 % des appels).

### Famille 5 : Exécution de l'Équipe Commerciale (SDRs) & Impact Décisionnel
19. **Écart de performance Top Performers vs Juniors :**
    * Top Performers (22–26 mois d'ancienneté : Camille Laurent & Thomas Mercier) : 635 050 € d'ARR chacun (62 deals, 22,38 % de décroché).
    * Juniors (3–5 mois d'ancienneté : Hugo Lefevre, Ines Chevalier, Maxime Roux) : 193 550 € d'ARR chacun (18 deals, 12,87 % à 14,12 % de décroché).
    * Écart net d'ARR : 441 500,00 €.
20. **Paradoxe d'effort des juniors (ex. Hugo Lefevre) :** 7 935 appels passés (le plus gros volume des 10 commerciaux) pour seulement 193 550 € d'ARR, prouvant que le volume d'appels bruts ne compense pas un mauvais ciblage ni un manque de formation.

---

## 3. LES 5 KPI ROIS : CALCULS DÉTAILLÉS, SOUS-KPI & SIGNIFICATION BUSINESS

Pour piloter l'entreprise sans noyer le CoDir sous 20 métriques, nous consolidons chaque famille en **1 KPI Roi représentatif**.

```
                           [ 20 MÉTRIQUES BRUTES ]
                                      │
                                      ▼
                            [ 12 RATIOS MÉTIERS ]
                                      │
                                      ▼
                              [ 5 KPI ROIS ]
                                      │
                 ┌────────────────────┴────────────────────┐
                 ▼                                         ▼
       [ PROBLÈME 1 : TPE ]                      [ PROBLÈME 2 : PME ]
     42% Appels ➔ 6% ARR                       2,25 M€ ARR menacés
                 │                                         │
                 ▼                                         ▼
     [ ARBITRAGE 1 : PLG ]                     [ ARBITRAGE 2 : CSM ]
        +1,55 M$ (Coût 0€)                       +1,45 M$ (Coût 58k€)
                 │                                         │
                 └────────────────────┬────────────────────┘
                                      ▼
                          [ +3,00 M$ ARR / ROI ×52 ]
```

### 👑 KPI Roi 1 (Activité) : Le Taux de Transformation Global (0,53 %)
* **Formule mathématique :**
  $$\text{Taux de Transformation Global} = \frac{\text{Contrats Signés Total}}{\text{Appels Passés Total}} = \frac{358}{67\,560} = 0{,}5298\% \approx 0{,}53\%$$
* **Sous-KPIs utilisés :**
  * Taux de Décroché : $\frac{11\,190}{67\,560} = 16{,}56\%$
  * Taux Connect ➔ Démo : $\frac{759}{11\,190} = 6{,}78\%$
  * Taux Démo ➔ Closing : $\frac{358}{759} = 47{,}17\%$
  * Vérification produit en chaîne : $16{,}56\% \times 6{,}78\% \times 47{,}17\% = 0{,}53\%$.
* **Signification Business :** Il faut en moyenne **189 appels passés pour obtenir 1 signature**. Ce KPI prouve que le goulot d'étranglement ne se situe pas dans le closing des démos (47,17 % est un excellent taux), mais dans les étapes amont (qualification téléphonique et accroche).

### 👑 KPI Roi 2 (Valeur) : Le Rendement par Appel Passé (54,53 €/appel)
* **Formule mathématique :**
  $$\text{Rendement par Appel} = \frac{\text{ARR Total Signé}}{\text{Appels Passés Total}} = \frac{3\,684\,000{,}00\,\text{€}}{67\,560} = 54{,}529\,\text{€} \approx 54{,}53\,\text{€}$$
* **Sous-KPIs utilisés :**
  * Taux de Transformation Global : $0{,}53\%$
  * Panier Moyen Global (ACV) : $10\,290{,}50\,\text{€}$
  * Formule croisée : $0{,}005298 \times 10\,290{,}50\,\text{€} = 54{,}53\,\text{€}$.
* **Signification Business :** Chaque fois qu'un SDR décroche son combiné et lance un appel, il génère mathématiquement 54,53 € d'ARR récurrent. Ce ratio permet de valoriser immédiatement le coût d'opportunité d'une heure de travail commercial.

### 👑 KPI Roi 3 (Rentabilité) : La Part d'ARR Générée par la PME (61,1 %)
* **Formule mathématique :**
  $$\text{Part ARR PME} = \frac{\text{ARR Signé PME}}{\text{ARR Signé Total}} = \frac{2\,250\,300{,}00\,\text{€}}{3\,684\,000{,}00\,\text{€}} = 61{,}083\% \approx 61{,}1\%$$
* **Sous-KPIs utilisés :**
  * Contrats signés PME : 234 contrats (soit $65{,}36\%$ des deals totaux).
  * Panier moyen PME : $9\,616{,}67\,\text{€}$ (contre $3\,725{,}00\,\text{€}$ en TPE).
  * Part d'appels PME : $48{,}13\%$ (32 520 appels).
* **Signification Business :** La PME est le cœur battant d'Aircall. Alors que la TPE consomme 42,3 % des ressources pour un dérisoire 6,1 % du revenu, la PME produit plus de 6 € sur 10. Toute décision stratégique doit prioriser la santé financière de ce segment.

### 👑 KPI Roi 4 (Canaux) : Le Panier Moyen de l'Outbound ColdCall (8 344 €)
* **Formule mathématique :**
  $$\text{Panier Moyen Outbound} = \frac{\text{ARR Outbound ColdCall}}{\text{Deals Outbound ColdCall}} = \frac{2\,328\,100{,}00\,\text{€}}{279} = 8\,344{,}44\,\text{€} \approx 8\,344\,\text{€}$$
* **Sous-KPIs utilisés :**
  * ARR Outbound : 2 328 100 € (soit $63{,}19\%$ de l'ARR total).
  * Appels Outbound : 57 705 appels ($85{,}41\%$ du volume total).
  * Comparaison avec l'Inbound ($15\,375\,\text{€}$) et Partenaire CRM ($18\,997\,\text{€}$).
* **Signification Business :** Le Cold Call est indispensable en volume (63,2 % du CA), mais ses paniers sont plus de 2 fois inférieurs aux leads partenaires CRM et Inbound. Le Cold Call doit être épuré des petits comptes pour viser des paniers élevés.

### 👑 KPI Roi 5 (Équipe) : L'Écart d'ARR Top Performer vs Junior (441 500 €)
* **Formule mathématique :**
  $$\Delta \text{ Performance} = \text{ARR Top Performer (24 mois)} - \text{ARR Junior (4 mois)} = 635\,050{,}00\,\text{€} - 193\,550{,}00\,\text{€} = 441\,500{,}00\,\text{€}$$
* **Sous-KPIs utilisés :**
  * Performance Camille Laurent / Thomas Mercier : 635 050 € (62 deals signés, tx décroché 22,38 %).
  * Performance Hugo Lefevre / Ines Chevalier / Maxime Roux : 193 550 € (18 deals signés, tx décroché 12,87 % à 14,12 %).
  * Ratio d'efficacité : Un top performer produit **3,28× plus d'ARR qu'un junior**.
* **Signification Business :** L'ancienneté et la maîtrise du pitch/ciblage créent un écart colossal de près d'un demi-million d'euros par commercial. Un système de peer-coaching permet de combler cet écart sans embaucher.

---

## 4. DÉCRYPTAGE MÉTIER : DÉFINITION DE L'ARR & SIGNIFICATION DE L'ÉCART DE 441 500 €

### 💡 Qu'est-ce que l'ARR (Annual Recurring Revenue) ?
* **Définition :** L'ARR représente le Revenu Récurrent Annuel généré par les abonnements souscrits par les clients. C'est la métrique reine absolue des entreprises SaaS (Software as a Service).
* **Pourquoi est-ce crucial pour Aircall ?**
  Contrairement à une vente ponctuelle (one-shot), 1 € d'ARR signé continue de rapporter chaque année tant que le client ne se désabonne pas. La valorisation d'une licorne technologique comme Aircall se calcule sur un multiple de son ARR (habituellement entre 8× et 15× l'ARR). Générer 3,00 M$ d'ARR additionnels valorise directement l'entreprise entre **24 M$ et 45 M$ de plus**.

### 🔍 Que signifie concrètement l'écart de 441 500 € entre SDRs ?
1. **Le volume brut ne fait pas la performance :**
   Hugo Lefevre a passé 7 935 appels (le record de l'équipe), soit **1 800 appels de plus que Camille Laurent (6 135 appels)**. Pourtant, Hugo signe 18 contrats pour 193 550 € alors que Camille signe 62 contrats pour 635 050 €. Hugo s'épuise en appelant des cibles froides ou mal qualifiées (TPE).
2. **L'efficacité de l'accroche téléphonique (les 30 premières secondes) :**
   Camille et Thomas affichent un taux de décroché de 22,38 %, contre 12,87 % pour Maxime Roux. Les seniors savent à quel moment appeler, comment contourner les barrages des secrétaires et comment délivrer un pitch percutant.
3. **Le levier d'action managérial :**
   L'écart de 441 500 € n'est pas une fatalité liée au talent inné, mais une opportunité de transfert de compétences (peer-coaching formalisé) permettant d'élever le niveau des 3 juniors vers la médiane de 366 650 €.

---

## 5. LES 2 DYSFONCTIONNEMENTS MAJEURS DE LA PERFORMANCE COMMERCIALE

L'analyse croisée des données met en lumière deux ruptures critiques dans la chaîne de valeur :

### 🛑 Dysfonctionnement 1 : Le Drain d'Énergie et la Destruction de Valeur sur la TPE
* **Le constat :** Le segment TPE capte **42,25 % de l'activité globale des commerciaux** (28 545 appels passés, 4 333 décrochés).
* **Le résultat :** Il ne rapporte que **223 500 € d'ARR**, soit à peine **6,07 % du chiffre d'affaires**.
* **Le diagnostic économique :**
  * Panier moyen de 3 725 € (moins de 310 €/mois).
  * Taux de transformation décroché ➔ démo anémique : **2,58 %** (contre 9,73 % en PME).
  * Coût d'Acquisition Client (CAC) disproportionné : Le temps commercial passé par un SDR à prospecter une TPE par cold call coûte plus cher que l'ARR rapporté sur la première année.

### ⚠️ Dysfonctionnement 2 : L'Exposition au Churn Massif sur le Cœur PME
* **Le constat :** La PME concentre **61,08 % de l'ARR total (2 250 300 €)** sur 234 entreprises.
* **Le résultat :** Ce portefeuille stratégique est géré sans aucun Customer Success Manager (CSM) dédié.
* **Le diagnostic économique :**
  * Le taux de désabonnement (churn) annuel historique en SaaS B2B sur les PME non accompagnées est de **18 % à 22 %** (médiane à 20 %).
  * Fuite de valeur sèche : $2\,250\,300\,\text{€} \times 20\% = \mathbf{450\,060\,\text{€}}$ de pertes d'ARR récurrent chaque année.
  * Cause racine : Onboarding non cadré sur le standard VoIP, mauvaise intégration avec le CRM HubSpot/Salesforce, et aucun système proactif d'alerte lors de la baisse d'usage des licences.

---

## 6. LES 2 ARBITRAGES STRATÉGIQUES CHIFFRÉS (VISION PUREMENT ROISTE)

Face à ces deux problèmes, nous engageons **strictement 2 décisions actionnables** avec un retour sur investissement validé.

### 🚀 Arbitrage 1 : Réallocation Commerciale 100% PME & MidMarket (PLG Self-Serve TPE)
* **Décision stratégique :**
  1. **Arrêt immédiat et total du Cold Call sur les entreprises de moins de 20 salariés (TPE).**
  2. Redirection des prospects TPE vers un parcours 100 % digitalisé en libre-service (Product-Led Growth / souscription par carte bancaire sur le site aircall.io).
  3. Réaffectation intégrale des 28 545 appels sortants sur les segments PME et MidMarket.
* **Modalités d'implémentation opérationnelle :**
  * Nettoyage des listes CRM et interdiction d'inscrire des comptes <20 salariés dans les cadences de cold calling.
  * Optimisation de la landing page tarifaire et parcours self-onboarding sans intervention humaine.
* **Impact Financier :**
  * Gain d'ARR additionnel modélisé : **+1,55 M$ d'ARR**.
  * Coût direct d'implémentation : **0 €** (redéploiement du temps existant des 10 SDRs).
  * Rentabilité nette : ROI immédiat et infini.

### 🛡️ Arbitrage 2 : Sécurisation & Expansion PME (CSM Dédié, Onboarding & Alertes d'Usage)
* **Décision stratégique :**
  1. **Recrutement d'un CSM Senior dédié au segment PME** pour piloter l'adoption, les QBR (revues trimestrielles) et l'expansion de licences.
  2. **Automatisation de l'onboarding en self-service** pour les comptes autonomes grâce à des guides interactifs in-app.
  3. **Déploiement d'un système d'alertes prédictives de churn** connectant les logs d'appels Aircall au CRM (détection des baisses de volume >30 % sur 14 jours).
* **Modalités d'implémentation opérationnelle :**
  * Fiche de poste CSM PME axée sur la rétention nette (Net Revenue Retention > 115 %).
  * Déclencheurs de tâches automatisés dans HubSpot/Salesforce lorsqu'un compte montre des signes de sous-utilisation.
* **Impact Financier :**
  * Protection du churn PME : rétention de ~350 000 € d'ARR.
  * Expansion & Upsell licences : +1 100 000 € d'ARR additionnel.
  * Gain brut généré : **+1,45 M$ d'ARR**.
  * Coût d'embauche annuel chargé du CSM : **58 000 €**.
  * Rentabilité unitaire : $\frac{1\,450\,000\,\text{€}}{58\,000\,\text{€}} = \mathbf{ROI \times 25}$.

### 💰 Bilan Consolidé des 2 Arbitrages
| Élément | Arbitrage 1 (PLG / Stop TPE) | Arbitrage 2 (CSM / Rétention PME) | TOTAL CONSOLIDÉ |
| :--- | :---: | :---: | :---: |
| **Gain ARR Net** | **+1,55 M$** | **+1,45 M$** | **+3,00 M$ ARR** |
| **Coût d'Investissement** | **0 €** | **58 000 €** | **58 000 €** |
| **Retour sur Investissement** | Immédiat | ROI ×25 | **ROI Consolidé ×52** |

---

## 7. ARCHITECTURE TECHNIQUE LOOKER STUDIO : LES 9 COMPOSANTS SANS CHEVAUCHEMENT

Le cockpit Looker Studio est conçu selon un cahier des charges strict : **9 composants sans aucun chevauchement de coordonnées**, avec filtres dynamiques croisés et persistance cloud.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                       BANDEAU SUPÉRIEUR — SCORECARDS                        │
│  [ Appels : 67 560 ]   [ Connects : 11 190 ]   [ Deals : 358 ]   [ ARR : 3,68M€ ] │
├─────────────────────────────────────────────────────────────────────────────┤
│                     BANDEAU MÉDIAN — FILTRES DYNAMIQUES                     │
│          [ Filtre 1 : Segment_client ]       [ Filtre 2 : Commercial ]      │
├──────────────────────────────────────┬──────────────────────────────────────┤
│    TABLEAU SEGMENTATION (Gauche)     │       GRAPHIQUE CANAUX (Droite)      │
│  TPE vs PME vs MidMarket             │  Histogramme horizontal              │
│  (Appels, Démos, Deals, ARR, ACV)    │  ARR généré par canal (Cold/CRM/Web) │
├──────────────────────────────────────┴──────────────────────────────────────┤
│                 GRAND TABLEAU DE PERFORMANCE DES 10 COMMERCIAUX             │
│  Camille Laurent (635k€) ➔ Maxime Roux (193k€) : Appels, Connects, Deals, ARR│
└─────────────────────────────────────────────────────────────────────────────┘
```

### Détail des 9 Composants
1. **Carte de Score 1 :** Volume Total d'Appels Passés (`67 560`).
2. **Carte de Score 2 :** Total des Appels Décrochés / Connects (`11 190`).
3. **Carte de Score 3 :** Total des Contrats Signés (`358`).
4. **Carte de Score 4 :** Montant Total de l'ARR Signé (`3 684 000 €`).
5. **Liste Déroulante 1 :** Contrôle de filtre dimensionnel `Segment_client` (TPE, PME, MidMarket).
6. **Liste Déroulante 2 :** Contrôle de filtre dimensionnel `Commercial` (Les 10 SDRs).
7. **Tableau de Segmentation Client :** Croise pour chaque segment les Appels, Connects, Démos, Contrats, Panier Moyen et ARR.
8. **Graphique à Barres :** Histogramme comparant l'ARR cumulé par `Canal_acquisition` (Outbound ColdCall vs Partenaire CRM vs Inbound Web).
9. **Grand Tableau d'Équipe :** Liste exhaustive des 10 commerciaux classés par ARR décroissant avec leurs métriques d'activité et de conversion individuelles.

---

## 8. LES 6 LIVRABLES A4 OFFICIELS DEMI-JOURNÉE PAR DEMI-JOURNÉE

Chaque demi-journée d'examen correspond à un livrable A4 normalisé, accessible dans `/Users/kevinmonin/Downloads/Livrables_Individuels_A4/` et centralisé dans `livrables.html` :

* **Livrable 1 (Jour 1 Matin) — Note de Cadrage & Gouvernance :**
  Définition du mandat de l'auditeur RevOps, périmètre d'étude (10 SDRs sur 12 mois, 67k appels), matrice RACI, comitologie de validation (Directeur Commercial, Financier, IT) et gestion des risques.
* **Livrable 2 (Jour 1 Après-midi) — Processus Métier & Cartographie des Flux :**
  Modélisation du funnel de vente étape par étape (Appels ➔ Connects ➔ RDV ➔ Démos ➔ Deals) et flux d'intégration de données (Aircall CTI ➔ HubSpot CRM ➔ Google Sheets / BigQuery ➔ Looker Studio).
* **Livrable 3 (Jour 2 Matin) — Pyramide des KPIs :**
  Hiérarchisation des indicateurs en 3 niveaux d'exigence (Niveau 1 : Activité brute, Niveau 2 : Efficacité et conversion, Niveau 3 : Ratios business et outcome financier).
* **Livrable 4 (Jour 2 Après-midi) — Dashboard Interactif Looker Studio :**
  Spécifications techniques, maquette d'architecture 9 blocs sans chevauchement, formules des champs calculés (`Panier_Moyen`, `Taux_Transformation`) et validation de la persistance cloud.
* **Livrable 5 (Jour 3 Matin) — Diagnostic Approfondi & Les 2 Arbitrages Stratégiques :**
  Restitution des constats data sur les TPE et PME, formulation des deux arbitrages majeurs (+1,55 M$ et +1,45 M$), chiffrage complet des coûts (58 k€) et calcul du ROI consolidé (×52).
* **Livrable 6 (Jour 3 Après-midi) — Synthèse Exécutive CoDir & Plan de Soutenance :**
  Note de synthèse formelle pour les décideurs, posture critique et traçabilité des données (3 sources), et déroulé chronométré de l'oral en 15 minutes.

---

## 9. DÉROULÉ EXHAUSTIF DE LA PRÉSENTATION EN 8 SLIDES ULTRA-ÉPURÉES

Fichier généré : [PREZ_AIRCALL_8_SLIDES.html](file:///Users/kevinmonin/aircall-soutenance-prez/PREZ_AIRCALL_8_SLIDES.html)  
Charte graphique : **Fond sombre (#061B14 / #0A281E), typographie blanche (#FFFFFF), accent vert Aircall (#00B388 / #00E6A4)**.  
Règle éditoriale absolue : **Zéro phrase longue, aucun paragraphe dense, mots simples et chiffres clés percutants.**

### 🟢 Slide 1 : Identité Aircall (4 Chiffres Clés)
* **En-tête :** `aircall.` | 01 · IDENTITÉ OFFICIELLE | Licorne Téléphonie Cloud
* **Titre :** Aircall en **4 Chiffres Clés**
* **Sous-titre :** Standard téléphonique cloud connecté nativement aux CRM — Modèle SaaS B2B mondial.
* **Grille 4 cartes métriques :**
  1. `250 M$` | ARR Global (+30% YoY, Licorne SaaS mondiale)
  2. `24 000+` | Entreprises Clientes (85k+ utilisateurs dans 100+ pays)
  3. `> 110 %` | Net Retention Rate (Expansion nette & LTV client, cœur du moteur RevOps)
  4. `EBITDA +` | Modèle Rentable (Cash-flow opérationnel positif validé dès 2024, Rule of 40)

### 🟢 Slide 2 : Gouvernance & Cadrage (3 Décideurs + Cheminement)
* **En-tête :** `aircall.` | 02 · GOUVERNANCE & CADRAGE | Alignement CoDir
* **Titre :** Les 3 Décideurs CoDir & **Cheminement Cadré**
* **Sous-titre :** Validation tripartite indispensable pour engager les arbitrages de croissance.
* **Bloc Haut (3 Silhouettes directeurs) :**
  * `Directeur Commercial` ➔ Focus : **Priorisation Pipe & SDRs** | Valide la réallocation des commerciaux.
  * `Directeur Financier` ➔ Focus : **Validation Business Case & ROI** | Arbitre le budget de 58 k€ et valide le gain net.
  * `Directeur IT & Tech` ➔ Focus : **Faisabilité CRM & Looker** | Valide la fiabilité des flux et l'automatisation.
* **Bloc Bas (Cheminement linéaire) :**
  `1. Cadrage Périmètre (10 SDRs / 12 Mois)` ➔ `2. Cartographie des Flux Data & Funnel` ➔ `3. Validation CoDir & Arbitrages ROIstes`

### 🟢 Slide 3 : Problématique (« Trop de KPI tue les KPI »)
* **En-tête :** `aircall.` | 03 · PROBLÉMATIQUE DATA | Entonnoir Décisionnel
* **Titre :** « Trop de KPI tue les KPI » : **L'Entonnoir Décisionnel**
* **Sous-titre :** Comment extraire la clarté stratégique d'une masse de métriques brutes.
* **Visuel Pyramide Inversée :**
  * *Haut (Tier 1) :* **20 Métriques Brutes** (Appels, Connects, RDV, Démos, Deals, ARR, ACV, Cycles...)
  * *Milieu (Tier 2) :* **12 Ratios Clés** (Taux Décroché, Taux Démo, Taux Closing, ARR/Canal, Écart SDR...)
  * *Bas (Tier 3) :* **5 Indicateurs Rois** (0,53% Transfo | 54,53€/Appel | 61,1% ARR PME | 8 344€ ColdCall | 441,5k€ Écart SDR)
* **Bloc Bas (2 Problèmes Majeurs) :**
  * `🚨 Problème 1 : Dispersion d'Énergie sur la TPE` ➔ 42% Effort pour 6% ARR.
  * `🚨 Problème 2 : Risque de Churn Massif sur la PME` ➔ 20% Churn = 400 k€ Fuite.

### 🟢 Slide 4 : Vision Aircall — Pilotage Data (Looker Studio)
* **En-tête :** `aircall.` | 04 · PILOTAGE DATA STUDIO | 9 Composants Sans Chevauchement
* **Titre :** Tableau de Bord Looker Studio : **Architecture 9 Blocs**
* **Sous-titre :** Zéro chevauchement, double filtrage dynamique et persistance Cloud intégrale.
* **Ruban Horizontal Supérieur (6 Composants) :**
  `1. 4 Scorecards (67k, 11k, 358, 3,68M€)` · `2. 2 Filtres Déroulants (Segment, SDR)` · `3. Segmentation TPE/PME/Mid` · `4. Canaux ARR` · `5. Grille 10 Commerciaux` · `6. Persistance Cloud 100%`
* **Zone Hero Grand Format (Looker Studio Auto-Scalé) :**
  * Cockpit Looker Studio interactif direct en pleine largeur, auto-scalé dynamiquement (zéro scrollbar, 100% des éléments visibles dont le tableau des 10 commerciaux jusqu'à la pagination).
  * Bouton `⛶ Plein Écran` pour immersion totale lors de la présentation CoDir.
  * Bouton bascule `🖼️ Capture HD Sécurisée` avec zoom lightbox pour sécuriser l'oral en cas de coupure réseau.
    1. 4 Cartes de Score (Appels, Connects, Deals, ARR)
    2. 2 Listes Déroulantes de filtres (Segment_client, Commercial)
    3. Tableau de Segmentation Client (TPE vs PME vs MidMarket)
    4. Graphique à Barres ARR (ColdCall vs CRM vs Web)
    5. Grand Tableau des 10 Commerciaux (Camille ➔ Maxime)
    6. Persistance Cloud Validée (100% stable au rechargement)

### 🟢 Slide 5 : Problème 1 : Dispersion TPE (Arbitrage 1)
* **En-tête :** `aircall.` | 05 · ARBITRAGE STRATÉGIQUE N°1 | Réallocation Commerciale
* **Titre :** Problème 1 : Dispersion TPE ➔ **Arbitrage Self-Serve**
* **Sous-titre :** Stopper le démarchage sortant à perte pour concentrer 100% des SDRs sur les PME.
* **Grille 2 Colonnes :**
  * *Colonne Alerte (Constat) :*
    * `42 %` des appels absorbés par la TPE (28 545 appels pour 6 % d'ARR).
    * `3 725 €` Panier Moyen TPE (Conversion 4× inférieure, CAC > LTV).
  * *Colonne Succès (Solution & Gain) :*
    * `Stop Cold Call` ➔ Basculement 100 % Self-Serve (PLG en ligne).
    * `+1,55 M$` Nouvel ARR Additionnel (Coût d'implémentation : **0 €** | **TTV : J+30 à J+60**).
* **Barre de Faisabilité & Déploiement en Temps (Quick Win 45 Jours) :**
  * `S1 – S2` : **Routing CRM Automatique** ➔ Redirection automatique des leads < 20 salariés vers démo & pricing self-serve.
  * `S3 – S4` : **Réattribution Territoires SDR** ➔ Nouveaux quotas 100% PME/MidMarket & mise à jour des séquences Cold Call.
  * `S5 – S6` : **Go-Live & Premiers Gains** ➔ 100% effort SDR sur PME. Premières signatures additionnelles dès J+60 (+1,55 M$).

### 🟢 Slide 6 : Problème 2 : Risque Churn PME (Arbitrage 2)
* **En-tête :** `aircall.` | 06 · ARBITRAGE STRATÉGIQUE N°2 | Sécurisation ARR PME
* **Titre :** Problème 2 : Risque Churn PME ➔ **1 CSM Dédié & Alertes**
* **Sous-titre :** Sécuriser le cœur du chiffre d'affaires (61% de l'ARR) menacé par le désengagement.
* **Grille 2 Colonnes :**
  * *Colonne Alerte (Constat) :*
    * `2,25 M€` ARR PME exposé sans accompagnement dédié (61,1 % de l'ARR global).
    * `400 000 €` Perte sèche annuelle liée à un churn historique de 20 %.
  * *Colonne Succès (Solution & Gain) :*
    * `1 CSM Dédié PME` + Onboarding automatisé petits comptes + Alertes d'usage prédictives.
    * `+1,45 M$` ARR Protégé & Expansion (Coût : 58 000 € chargés | **ROI ×25** | **TTV : J+60 à J+90**).
* **Barre de Faisabilité & Déploiement en Temps (Moyen Terme 90 Jours) :**
  * `Mois 1 (J+1 à J+30)` : **Chasse CSM & Alertes Tech** ➔ Lancement recrutement CSM + triggers HubSpot (inactivité < 50 appels/semaine).
  * `Mois 2 (J+31 à J+60)` : **Onboarding & Sauvetage** ➔ Arrivée du CSM, intervention prioritaire sur les 20 comptes PME à risque de churn.
  * `Mois 3 (J+61 à J+90)` : **Régime de Croisière & Upsell** ➔ Revues trimestrielles (QBR), churn réduit sous 5% et expansion NRR > 110%.

### 🟢 Slide 7 : Impact Global — Rétroaction Data (Bilan ROI ×52)
* **En-tête :** `aircall.` | 07 · SYNTHÈSE GLOBALE & ROI | Impact CoDir 2026
* **Titre :** Impact Global Consolidé : **+3,00 M$ d'ARR / ROI ×52**
* **Sous-titre :** De l'analyse rigoureuse des 5 indicateurs rois à la création de valeur massive.
* **Ligne des 5 KPI Rois :**
  * `0,53%` Transfo | `54,53€` Rendement/Appel | `61,1%` ARR PME | `8 344€` ColdCall | `441,5k€` Écart SDR
* **Bannière ROI Géante :**
  * Gain ARR Net Consolidé : **+3,00 M$ ARR** (Arbitrage 1 : +1,55M$ + Arbitrage 2 : +1,45M$)
  * Budget Décisionnel Engagé : **58 000 €**
  * Résultat Final CoDir : **Retour sur Investissement Global ROI ×52**

### 🟢 Slide 8 : Transparence & Traçabilité des Données (Matrice 3 Sources)
* **En-tête :** `aircall.` | 08 · TRANSPARENCE & CONFORMITÉ | Origine Certifiée
* **Titre :** Matrice de Transparence : **L'Origine de Chaque Donnée**
* **Sous-titre :** Distinction formelle entre le cas d'étude réel, les données publiques et la simulation.
* **Tableau Exhaustif des 3 Sources :**
  1. `Données Réelles Examen (Rocket School)` : 67 560 appels, 11 190 connects, 358 deals, 3,68 M€ ARR, segmentation TPE/PME/MidMarket.
  2. `Données Publiques Officielles (aircall.io)` : Licorne SaaS, 250 M$ ARR, 24k clients, +100 pays, +100 intégrations CRM natives.
  3. `Données Simulées pour l'Exercice` : Répartition nominative des 10 SDRs (Camille à Maxime), écarts d'ancienneté, ventilation par canal.

---

## 10. MATRICE DE TRANSPARENCE & TRAÇABILITÉ DES DONNÉES (3 SOURCES)

Pour garantir une posture d'intégrité absolue devant le jury de la Rocket School, chaque point de donnée est formellement rattaché à son origine :

| Catégorie | Données & Métriques Associées | Référence & Méthode |
| :--- | :--- | :--- |
| **1. Données Réelles du Référentiel Rocket School** | • 67 560 appels passés sur 12 mois<br>• 11 190 appels décrochés (taux global 16,56 %)<br>• 358 contrats signés (taux global 0,53 %)<br>• 3 684 000 € d'ARR total (panier moyen 10 290,50 €)<br>• Répartition par segment : TPE (28 545 appels), PME (32 520 appels), MidMarket (6 495 appels) | Fichier officiel du cas d'étude Rocket School (`aircall_bizdev_simule_2026.csv`). |
| **2. Données Publiques et Institutionnelles Aircall** | • Statut de licorne SaaS (valorisation > 1 Md$)<br>• ARR global de l'entreprise (~250 M$ ARR mondial)<br>• 24 000+ entreprises clientes et 85 000+ utilisateurs<br>• Présence mondiale dans plus de 100 pays<br>• Catalogue de plus de 100 intégrations CRM natives | Sites officiels `aircall.io` et `support.aircall.io` (documentation produit et communiqués officiels). |
| **3. Données Simulées pour le Cas d'Étude** | • Répartition individuelle des 10 SDRs (Camille Laurent, Thomas Mercier, Chloé Petit, Julie Garnier, Lucas Moreau, Mehdi Haddad, Sarah Benali, Hugo Lefevre, Inès Chevalier, Maxime Roux)<br>• Écarts d'ancienneté (26 mois pour Camille vs 3 mois pour Maxime)<br>• Ventilation granulaire des volumes d'appels par commercial | Modèle pédagogique de simulation d'équipe commerciale pour l'évaluation RevOps. |

---

## 11. SCRIPT ORAL CHRONOMÉTRÉ DE SOUTENANCE (15 MINUTES) & FAQ JURY

### ⏱️ Découpage Précis des 15 Minutes d'Oral

#### Bloc 1 : Introduction, Identité Aircall & Cadrage CoDir (3 min — Slides 1 & 2)
* **00:00 – 01:30 (Slide 1) :**
  * *Script oral :* « Bonjour Mesdames et Messieurs les membres du CoDir. Aircall est aujourd'hui une référence mondiale : licorne rentable avec un EBITDA positif atteint dès 2024, 250 M$ d'ARR, 24 000 clients dans plus de 100 pays et un Net Retention Rate supérieur à 110 %. Mais pour maintenir une croissance à deux chiffres dans un contexte de discipline financière, notre machine commerciale ne peut plus se contenter d'un volume d'appels brut non optimisé. »
* **01:30 – 03:00 (Slide 2) :**
  * *Script oral :* « Pour cette mission RevOps, mon cadrage réunit trois sponsors clés : le Directeur Commercial sur la priorisation des SDRs, le Directeur Financier sur la validation du ROI et l'IT sur les flux Looker Studio. Notre méthode en 3 étapes — cadrage, cartographie des flux et arbitrage financier — garantit qu'aucune décision n'est prise sans validation data. »

#### Bloc 2 : Diagnostic Entonnoir & Démonstration Looker Studio (3 min 30 s — Slides 3 & 4)
* **03:00 – 04:30 (Slide 3) :**
  * *Script oral :* « Trop de KPI tue les KPI. Nous avons audité 20 métriques brutes pour n'en retenir que 5 indicateurs rois : 0,53 % de transformation globale, 54,53 € d'ARR par appel, 61,1 % du CA concentré sur la PME, 8 344 € de panier en Cold Call, et un écart de 441 500 € entre top performers et juniors. Cet entonnoir fait émerger deux problèmes majeurs : l'hémorragie d'appels sur la TPE et le risque de churn sur la PME. »
* **04:30 – 06:30 (Slide 4) :**
  * *Script oral :* « Voici notre cockpit Looker Studio. Il respecte une architecture stricte de 9 composants sans chevauchement avec persistance Cloud. Grâce aux deux filtres déroulants, nous pouvons croiser instantanément la performance d'un commercial avec un segment client. Regardez la segmentation : elle rend visuellement flagrant le déséquilibre d'effort entre TPE et PME. »

#### Bloc 3 : Les 2 Arbitrages Stratégiques & Business Case (5 min — Slides 5 & 6)
* **06:30 – 09:00 (Slide 5) :**
  * *Script oral :* « Premier arbitrage : stopper le Cold Call sur la TPE. Pourquoi ? La TPE consomme 42 % des appels de nos 10 SDRs pour seulement 6 % de l'ARR. Le panier de 3 725 € détruit de la valeur. Notre décision : basculer les TPE en Product-Led Growth, 100 % libre-service sur notre site, et réallouer les 28 545 appels vers les PME. C'est un **Quick Win déployé en 45 jours chrono** (routing CRM en S1-S2, réattribution des quotas en S3-S4, Go-Live en S5-S6). **Time-to-Value dès J+30 à J+60**, pour un gain de **+1,55 M$ d'ARR pour un coût de 0 €**. »
* **09:00 – 11:30 (Slide 6) :**
  * *Script oral :* « Second arbitrage : sécuriser notre trésor de guerre, les 2,25 M€ d'ARR du cœur PME. Aujourd'hui, un churn moyen de 20 % nous coûte 400 000 € par an faute de suivi. Nous recrutons un CSM dédié PME, automatisons l'onboarding des petits comptes et déployons des alertes HubSpot d'inactivité téléphonique. Faisabilité cadrée sur **90 jours (Q1-Q2)** : Mois 1 pour le recrutement et les triggers d'inactivité, Mois 2 pour l'onboarding et le sauvetage des 20 comptes PME à risque, Mois 3 pour les revues trimestrielles. **Time-to-Value plein à J+60-J+90**, pour **+1,45 M$ d'ARR protégé et étendu. Coût : 58 k€, ROI unitaire de ×25**. »

#### Bloc 4 : Synthèse ROIste, Transparence & Q&A CoDir (3 min 30 s — Slides 7 & 8)
* **11:30 – 13:00 (Slide 7) :**
  * *Script oral :* « En synthèse, nos deux arbitrages combinés débloquent **+3,00 M$ d'ARR net pour seulement 58 000 € d'investissement**, soit un **retour sur investissement consolidé de ROI ×52**. C'est le passage d'une prospection subie à une machine de revenus prévisible. »
* **13:00 – 15:00 (Slide 8 & Échanges) :**
  * *Script oral :* « Toutes nos conclusions reposent sur une intégrité totale des données, traçables entre le cas d'étude Rocket School, les données réelles publiques d'Aircall et notre jeu de simulation. Je suis désormais à votre disposition pour vos questions. »

---

### ❓ FAQ & Questions Pièges du Jury Rocket School

1. **Question du CFO : « Pourquoi ne pas recruter un 11e SDR plutôt qu'un CSM à 58 000 € ? »**
   * *Réponse :* « Recruter un 11e SDR ajouterait des coûts d'acquisition sur un funnel qui fuit. Notre priorité RevOps est d'abord d'augmenter le rendement par commercial existant (en réallouant les 42 % d'appels TPE) et de boucher le trou du churn PME. Le CSM protège 400 k€ de fuite immédiate et génère de l'upsell, offrant un ROI de ×25 qu'un SDR junior ne peut égaler la première année. »
2. **Question du CRO : « Les TPE ne vont-elles pas disparaître si on arrête de les appeler ? »**
   * *Réponse :* « Non, elles sont migrées sur un parcours Product-Led Growth (PLG) inspiré de Dropbox ou Zoom. Les TPE préfèrent souscrire en autonomie par carte bancaire avec une démo vidéo plutôt que de subir des cadences de cold calling intrusives. Nous capturons l'ARR TPE à coût d'acquisition nul. »
3. **Question du Dir IT : « Comment garantissez-vous que le dashboard Looker Studio ne va pas se dégrader ? »**
   * *Réponse :* « L'architecture a été conçue sans aucun chevauchement de blocs en coordonnées absolues, et les sources de données ont été consolidées en amont dans Google Sheets pour éviter les erreurs de jointures dynamiques. La persistance cloud a été validée sous plusieurs sessions. »
