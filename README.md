📊 Superstore Analytics — Data Preparation Project
📌 Contexte

Ce projet s’inscrit dans le cadre de la préparation et du nettoyage des données de ventes d’une entreprise multi-catégories (mobilier, fournitures de bureau, technologie).

Les données initiales sont issues d’un fichier CSV brut contenant plusieurs problèmes :

Valeurs manquantes

Doublons

Incohérences de formats (dates, numériques)

Colonnes mal structurées

Absence d’indicateurs métier

L’objectif est de transformer ces données en un dataset propre et exploitable pour l’analyse et la prise de décision.

🎯 Objectifs du projet

Importer et analyser la structure du fichier store.csv

Nettoyer les données (valeurs manquantes, doublons, formats)

Appliquer des transformations et du feature engineering

Calculer des indicateurs métiers (KPI)

Exporter un dataset final prêt pour SQL et visualisation

🔄 Cycle de vie de la donnée

Le projet suit les étapes suivantes :

Ingestion

Lecture du fichier CSV avec Pandas

Nettoyage

Gestion des valeurs manquantes

Suppression des doublons

Correction des types de données

Harmonisation des formats

Transformation & Feature Engineering

Extraction année, mois, trimestre

Calcul de la marge et du taux de profit

Création d’indicateurs de performance

Agrégation des ventes par catégorie, région et produit

Export

Vérification de la cohérence

Export du fichier final superstore_clean.csv

📈 KPIs analysés
Direction Commerciale

Chiffre d’affaires total

Profit total

Marge moyenne

Ventes par catégorie

Ventes par région

Top 10 produits

Croissance mensuelle

Direction Financière

Profit moyen

Profit minimum / maximum

Écart-type des profits

Analyse des produits à faible marge

Détection des valeurs aberrantes

🛠️ Technologies utilisées

Python 3.x

Pandas

NumPy

Jupyter Notebook

✅ Livrables

Dataset nettoyé : superstore_clean.csv

Notebook documenté

Rapport PDF explicatif

Suivi des tâches via Jira

📌 Résultat

Le dataset final est propre, structuré et prêt à être utilisé dans une base SQL ou un outil de visualisation (Power BI, Tableau, etc.) afin de soutenir la prise de décision stratégique.
