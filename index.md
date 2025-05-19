# Portfolio Data Analyst – Hasna TAZI

**Nom** : TAZI Hasna  
**Profil** : Data Analyst | Communication & Stratégie | Reconversion professionnelle  
**Localisation** : Bordeaux – France  
**Email** : tazi.hasna@orange.fr  
**LinkedIn** : [www.linkedin.com/in/hasna-tazi-fr](https://www.linkedin.com/in/hasna-tazi-fr)  

---

## 🎓 À propos

Forte d’un parcours de plus de 20 ans en communication stratégique et relations clients, j’ai choisi de me réinventer dans l’univers de la data pour allier rigueur analytique, sens business et narration éclairée.

Ce portfolio est le reflet d’un cheminement personnel et professionnel engagé : une reconversion construite autour de projets concrets, de problématiques variées, et d’une volonté constante de rendre la donnée compréhensible, utile et exploitable.

💡 Il rassemble les projets les plus représentatifs de mon évolution dans la data : analyses e-commerce, exploration clients, dataviz dynamiques, tests statistiques et modélisation patrimoniale.

---

## 👩‍💻 Introduction

🎯 Ce portfolio réunit cinq projets phares réalisés au cours d’un bootcamp intensif en data analysis. Chacun d’eux illustre une facette complémentaire du métier de Data Analyst :

- **Projet 1** : analyse SQL avancée d’un dataset e-commerce complexe  
- **Projet 2** : dataviz dynamique avec Power BI sur des données multi-tables  
- **Projet 3** : analyse de performance locative Airbnb (BigQuery + Looker Studio)  
- **Projet 4** : exploration et A/B testing avec Python (Olist)  
- **Projet 5** : simulation patrimoniale avec projection Monte Carlo (finance personnelle)

---

## 🌟 Projet 1 : Analyse des données e-commerce de Olist

### 🧩 Contexte et objectifs
L’objectif de ce projet était d’analyser les données d’Olist, une plateforme e-commerce brésilienne, afin de répondre à des problématiques stratégiques : comportement client, performance produit, efficacité logistique et satisfaction.

### 📊 Données utilisées
-  Base de données relationnelle avec 9 tables (commandes, produits, clients, vendeurs, livraisons, avis…)
-  Données importées dans BigQuery
-  Format : CSV
-  Volume : ~100 000 lignes

### 🛠 Compétences techniques mobilisées
-  SQL avancé (jointures, agrégations, window functions, subqueries, CASE, GROUP BY, HAVING)
-  Exploration et nettoyage des données
-  Analyse descriptive et calculs de KPIs : CLV, AOV, CAC, délais de livraison, taux de satisfaction
-  Présentation des résultats et recommandations stratégiques

### 🧮 Démarche analytique
1.  Compréhension du contexte business et définition des questions clés
2.  Exploration et nettoyage des données
3.  Analyse ciblée sur :
  -  Comportement des clients : fréquence d’achat, panier moyen
  -  Performance produit : meilleures ventes, satisfaction A
  -  Analyse géographique : régions les plus rentables
  -  Suivi des délais et de la satisfaction client

### 📊 Résultats / Insights clés
-  Les clients fidèles génèrent en moyenne 3 fois plus de chiffre d’affaires que les clients uniques
-  Les délais de livraison longs sont fortement corrélés aux avis négatifs
-  Les produits électroniques génèrent un bon chiffre d’affaires mais reçoivent des notes inférieures à la moyenne

### 💡 Recommandations
-  Mettre en place un programme de fidélité pour les clients à forte valeur
-  Cibler les vendeurs avec des délais longs pour améliorer la satisfaction
-  Mieux encadrer les descriptions des produits électroniques pour éviter les déceptions

### 🎓 Ce que j’ai appris
-  Structurer une analyse SQL autour d’objectifs business clairs
-  Identifier et présenter des insights pertinents de manière synthétique
-  Travailler en équipe et restituer oralement un projet data

  
---

## 🌟 Projet 2 : Analyse Look E-commerce avec Power BI

### 🧩 Contexte et objectifs
Dans le cadre d’un atelier orienté storytelling data, l’objectif était d’identifier les facteurs influençant le taux de location sur Airbnb Paris, en analysant les disponibilités, prix, types de logement, et indicateurs de qualité (notes, temps de réponse…).

### 📊 Données utilisées
- 2 tables :
  .  listings: 1 ligne par location avec informations statiques (type, score, temps de réponse…)
  .  calendar: 1 ligne par jour et par logement avec prix, disponibilité
- Données analysées dans BigQuery et visualisées dans Looker Studio
- Période : année complète pour Paris

### 🛠 Compétences techniques mobilisées
-  Jointures SQL entre listings et calendar
-  Agrégations par logement (taux d’occupation, prix moyen…)
-  Création d’indicateurs clés (occupation rate, revenus potentiels)
-  Représentations visuelles dynamiques dans Looker Studio (courbes, cartes, annotations)
-  Storytelling analytique orienté “business insights”

### 🧮 Démarche analytique
-  Exploration des données brutes dans BigQuery
-  Jointure des tables sur listing_id pour croiser données statiques et dynamiques
-  Création de métriques par logement :
-  Taux d’occupation (% de jours réservés)
-  Prix moyen par nuit
-  Score moyen et temps de réponse
-  Étude de la corrélation entre performance locative et ces indicateurs
-  Création d’un dashboard Looker Studio pour raconter visuellement l’analyse

### 📊 Résultats / Insights clés
-  Les logements “entire home” ont un taux d’occupation plus élevé que les “private rooms”
-  Le taux d’occupation est fortement corrélé à un temps de réponse rapide de l’hôte
-  Les logements notés au-dessus de 9/10 ont un revenu potentiel 30 % supérieur à la moyenne
-  Les hausses de prix ne réduisent pas nécessairement le taux de location s’il y a une bonne note et un bon emplacement
https://lookerstudio.google.com/reporting/13471aa4-8bde-4b4b-8135-d159445b3642 

### 💡 Recommandations
-  Former les hôtes à améliorer leur réactivité pour augmenter leurs chances de réservation
-  Optimiser les tarifs pendant les périodes creuses grâce à une stratégie dynamique de pricing
-  Valoriser les notes et avis clients pour mieux classer les logements dans les résultats de recherche

### 🎓 Ce que j’ai appris
-  Manipuler et croiser efficacement plusieurs sources de données dans BigQuery
-  Explorer des corrélations simples mais pertinentes à partir de données partielles
-  Raconter une histoire business claire via des visualisations dans Looker Studio
-  Travailler en binôme sur une problématique analytique concrète avec restitution orale


---

## 🌟 Projet 3 : Analyse Airbnb Paris (BigQuery + Looker Studio)

### 🧩 Contexte et objectifs
Dans ce projet, nous avons analysé un dataset complet simulant les opérations d’un site e-commerce de prêt-à-porter ("The Look") pour en extraire des insights clés sur les ventes, le comportement client, les performances des produits et l’efficacité des campagnes marketing.

### 📊 Données utilisées
- Base de données multi-tables :
 .  Commandes, produits, utilisateurs, inventaire, événements web, marketing, etc.
- Source : BigQuery → connexion Power BI Desktop
- Volume : plusieurs dizaines de milliers de lignes
- Visualisation et modélisation dans Power BI

### 🛠 Compétences techniques mobilisées
-  Connexion à BigQuery depuis Power BI
-  Nettoyage des données via Power Query Editor
-  Modélisation relationnelle dans Power BI (vue modèle)
-  Calcul de KPIs : revenus, taux de retour, AOV, taux de conversion, ROI marketing…
-  Segmentation clients et produits
-  Représentations visuelles interactives (cartes, graphes, tableaux croisés dynamiques)

### 🧮 Démarche analytique
-  Compréhension du contexte métier : étude du modèle e-commerce de "The Look"
-  Choix des axes d’analyse prioritaires : ventes, comportement client, performance produit
-  Exploration des données :
  -  Analyse des ventes par catégorie, période, canal
-  Segmentation des clients selon les dépenses, zones géographiques, comportements
-  Taux de retour et turnover produit
-  Création de visualisations interactives et dashboard
-  Présentation des recommandations pour améliorer les performances globales

### 📊 Résultats / Insights clés
-  Le top 3 des catégories génère plus de 65 % du chiffre d'affaires annuel
-  Les retours produits sont concentrés sur certaines marques → problèmes qualité ou sizing
-  Les clients fidélisés (3+ commandes) ont un panier moyen 40 % supérieur
-  Les campagnes emailing génèrent un ROI 2 fois supérieur aux publicités sociales
  
### 💡 Recommandations
-  Optimiser les stocks sur les catégories à forte rotation et réduire les produits à retour élevé
-  Renforcer les actions marketing ciblées sur les clients fidèles
-  Réduire les investissements sur les canaux peu rentables (ex : réseaux sociaux) au profit de l’emailing
-  Améliorer les descriptions produits sur les articles les plus retournés
  
### 🎓 Ce que j’ai appris
-  Utiliser Power BI en situation réelle avec des données complexes et variées
-  Nettoyer et modéliser efficacement un dataset multi-sources
-  Définir des objectifs analytiques clairs orientés décisionnel
-  Présenter des recommandations pertinentes et actionnables en peu de temps


---

## 🌟 Projet 4 : A/B Testing & Statistiques sur les données d’Olist

### 🧩 Contexte et objectifs
Ce projet d’une journée avait pour objectif d’explorer un sous-ensemble du dataset public Olist (Brésil) afin de formuler des hypothèses business, d’extraire des insights descriptifs et de tester des hypothèses à l’aide de méthodes statistiques et d’A/B testing. L’approche reposait sur une analyse en Python (pandas, numpy, plotly express) et incluait une restitution orale des résultats.

### 📊 Données utilisées
- Données Olist (version réduite : commandes, clients, produits, paiements, évaluations)
- Données traitées dans un DataFrame après exploration et nettoyage

### 🔍 Méthodologie
1. **Exploration & nettoyage** : types de données, valeurs manquantes, doublons
2. **Statistiques descriptives** :
   - Prix moyen/écart-type/boîtes à moustaches (commande)
   - Répartition par catégorie produit, mode de paiement, satisfaction client
   - Analyse des délais de livraison (moyenne, médiane, écart-type)
3. **Corrélations exploratoires** :
   - Prix vs satisfaction
   - Délai de livraison vs satisfaction
   - Catégorie produit vs note
4. **A/B Testing (exemples)** :
   - Livraison à temps vs satisfaction moyenne (t-test)
   - Méthode de paiement vs taux de complétion commande (chi²)
   - Catégories produit vs valeur commande (ANOVA)

### 📈 Résultats
- Les délais de livraison ont un **impact significatif sur la satisfaction client** (p-value < 0.05)
- Certaines **catégories produit influencent la note moyenne** donnée par les clients
- Aucune différence significative détectée entre les méthodes de paiement sur le taux de commande finalisée

### 📌 Outils  
Python (pandas, numpy, plotly, scipy.stats), Jupyter

### 🗣️ Présentation  
Slides synthétiques avec visualisations + explication des tests


---

## 🌟 Projet 5 : Analyse comparative des investissements patrimoniaux

### 🧩 Contexte et objectifs
Ce projet de fin de bootcamp vise à analyser différentes stratégies d’investissement (unités de compte, fonds euros, immobilier, or) sur une période 2014–2024, avec projection à 2034. L’objectif est d’évaluer leurs performances, leurs risques et leur potentiel à long terme dans une optique de conseil patrimonial.

### 📊 Données utilisées
- ETF indiciels (unités de compte)
- Prix de l’or (GC=F – Yahoo Finance)
- Fonds euros (rapports assureurs)
- Prix immobilier (DVF open data)

### 🔍 Méthodologie
- Webscraping, nettoyage des séries temporelles, réconciliation des formats
- Visualisation des performances par support (2014–2024)
- Simulation de projection (2034) via modèles Monte Carlo
- Application d’algorithmes pour identifier les portefeuilles optimaux :
   .  Max rendement
   .  Min volatilité
   .  Max Sharpe Ratio
   .  Portefeuille équilibré

### 📈 Résultats clés
- L’or et les unités de compte affichent les meilleures performances 2014–2024
- Le portefeuille optimal (Sharpe) atteindrait 48 465 € en 2034 (vs 10 000 € en 2014)
- Le fonds euros reste très sécurisé mais peu performant (11 168 € projeté en 2034)

### 📌 Outils  
Python (yfinance, numpy, pandas, matplotlib, seaborn), Google Colab

### 🗣️ Présentation  
Storytelling visuel sur Canva, modélisation comparative, triangle performance/sécurité/disponibilité
---

## 🔗 Ressources

- [Notebook Projet 4 (Olist A/B testing)](https://colab.research.google.com/drive/1kvJnW5XAJ0L8lQZz3BWQImi540cSNBfq?usp=sharing)  
- [Présentation projet final (Investissement)](https://www.canva.com/design/DAGbCRDbI3o/IzGdMNo_f03Wozrop3Owtw/edit)  
- [Dashboard Looker Studio (Airbnb Paris)](https://lookerstudio.google.com/reporting/13471aa4-8bde-4b4b-8135-d159445b3642)  

---

© 2025 Hasna TAZI – Tous droits réservés.
