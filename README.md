Projet PFE – Atlas Commerce SARL

Analyse de données & Recommandations stratégiques

Catégorie : Data Analysis / Audit / Business Intelligence

🏢 Contexte

Atlas Commerce SARL est une entreprise e-commerce panafricaine opérant dans plusieurs grandes villes d’Afrique francophone. Elle vend des produits dans 4 catégories :

Électronique

Mode

Beauté

Maison

La direction a constaté plusieurs problématiques :

Variations importantes du chiffre d’affaires

Taux de retour élevé sur certains produits

Dépenses marketing importantes

Différences de performance selon les villes

Mission : Fournir une analyse stratégique complète pour soutenir la prise de décision commerciale.

🎯 Objectifs du projet

Produire un notebook Python propre et structuré.

Créer des visualisations professionnelles et interactives.

Rédiger un résumé exécutif clair et concis.

Fournir des recommandations concrètes et actionnables.

Développer un tableau de bord interactif pour la direction.

📦 Contenu du repository

data/ : Datasets bruts et nettoyés

notebooks/ : Notebook Python analysant les données étape par étape

reports/ : Résumé exécutif et recommandations (PDF)

dashboard/ : Tableau de bord interactif (ex: Streamlit ou Power BI export)

README.md : Présentation du projet

📝 Étapes du projet

1️⃣ Audit & Compréhension des données

Analyse de la structure et des types de données

Détection des valeurs manquantes, doublons et aberrantes

Identification des problèmes de qualité

Livrable : Résumé d’audit avec les problèmes détectés

2️⃣ Nettoyage des données (Data Cleaning)

Standardisation des dates

Uniformisation des catégories et des statuts

Correction des villes mal orthographiées

Gestion des remises négatives et des prix aberrants

Suppression ou traitement des quantités nulles

Traitement des doublons

Livrable : Dataset propre df_clean

3️⃣ Feature Engineering

Création de nouvelles variables :

chiffre_affaires

marge_brute

profit_net_estimé

augmentation_mois

indicateur_retour

nombre_commandes_par_client

valeur_vie_client (CLV simplifiée)

4️⃣ Analyses demandées

📊 Performance globale

Chiffre d’affaires total

Profit net

Panier moyen

Taux d’annulation

Taux de retour

🏷 Analyse par catégorie

CA et marge par catégorie

Taux de retour par catégorie

Évolution mensuelle

Question stratégique : Quelle catégorie prioriser ou optimiser ?

🌍 Analyse géographique

CA et profit par ville

Taux d’annulation par ville

Croissance mensuelle

Question stratégique : Où investir davantage ?

📢 Analyse marketing

CA par canal

Coût marketing par canal

ROI par canal

Taux de rétention par canal

Formule ROI :

ROI=
Co
u
^
t_marketing
Revenus−Co
u
^
t_marketing
	​

	​


Question stratégique : Quel canal mérite plus de budget ? Lequel optimiser ou réduire ?

👥 Analyse clients

Nombre total de clients

% clients récurrents

Analyse Pareto (80/20)

Top 10 clients

Segmentation simple
Question stratégique : Comment améliorer la rétention client ?

5️⃣ Visualisations

Bibliothèques : Matplotlib, Seaborn

Graphiques clairs et professionnels :

Diagrammes à barres

Graphiques linéaires

Graphiques de distribution

Heatmaps (cartes thermiques pertinentes)

📊 Livrables finaux

Notebook Python propre et commenté

Résumé exécutif (1 page maximum)

5 recommandations stratégiques concrètes

Conclusion orientée business

Tableau de bord interactif

⚡ Recommandations stratégiques (exemple)

Prioriser la catégorie avec le meilleur CA et marge, réduire les produits à fort taux de retour.

Investir dans les villes à forte croissance et fort potentiel de profit.

Optimiser les canaux marketing avec ROI faible et renforcer ceux à ROI élevé.

Développer des stratégies de fidélisation pour les clients récurrents.

Ajuster les remises et promotions pour maximiser la marge nette.

💻 Technologies utilisées

Python (Pandas, NumPy)

Visualisation (Matplotlib, Seaborn, Plotly)

Tableau de bord : Streamlit / Power BI
