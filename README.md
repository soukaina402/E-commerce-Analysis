🎯 Objectif du projet

Ce projet a été conçu pour démontrer la maîtrise complète du cycle BI avec Power BI :

Data Cleaning (Power Query)

Modélisation analytique

DAX avancé (Time Intelligence)

Design de dashboards interactifs

Analyse de performance e-commerce

🧩 Contenu du projet

Le modèle repose sur un schéma en étoile constitué de 5 fichiers CSV :

FactSales.csv – Transactions de ventes (400 lignes)

DimCustomer.csv – Clients

DimProduct.csv – Produits, catégories et sous-catégories

DimRegion.csv – Régions géographiques

DimDate.csv – Calendrier (2022–2024)

Les données sont exprimées en Dinars Tunisiens (TND).

🔄 ETL – Power Query

Les données ont été entièrement nettoyées et standardisées :

Dimensions

Suppression des espaces superflus

Uniformisation de la casse (Proper Case)

Normalisation des catégories (ex: fashion → Fashion)

FactSales

Remplacement de unknown par null dans UnitPrice_TND

Conversion de 10% en 0.10 pour Discount

Correction et typage des dates

Nettoyage du champ Région
