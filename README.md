# 🎮 Projet Steam — Analyse de l'écosystème du jeu vidéo

**Jedha Bootcamp · Certification CDSD · Bloc Big Data**

## 📋 Contexte

Analyse exploratoire des données de la plateforme Steam réalisée pour Ubisoft,
éditeur français de jeux vidéo souhaitant comprendre les tendances du marché
avant de lancer un nouveau jeu révolutionnaire.

## 🎯 Objectifs

Comprendre les facteurs qui influencent la popularité et les ventes d'un jeu vidéo
à travers 3 niveaux d'analyse :

- **Analyse Macro** : éditeurs, prix, sorties par année, restrictions d'âge
- **Analyse des Genres** : genres populaires, ratio avis, rentabilité
- **Analyse des Plateformes** : disponibilité Windows / Mac / Linux

## 📊 Dataset

- **Source** : [Steam Games Dataset — Kaggle](https://www.kaggle.com/datasets/nikdavis/steam-store-games)
- **Volume** : 27 075 jeux · 18 colonnes · 0 valeur nulle
- **Couverture** : jusqu'en 2019

## 🔑 Résultats Clés

| Analyse | Insight principal |
|---------|-----------------|
| Macro | Big Fish Games = top éditeur (212 jeux) · Pic de sorties en 2018 (8 160 jeux) |
| Prix | 54% des jeux payants coûtent moins de 5€ |
| Genres | Indie = 71% du catalogue · Portal 2 = 98.65% d'avis positifs |
| Plateformes | 68% des jeux sont exclusifs Windows · seulement 17% multi-plateformes |

## 🛠️ Stack Technique

- **Apache Spark / PySpark** — transformations et agrégations
- **Databricks** (Serverless Warehouse + Unity Catalog)
- **Matplotlib** — visualisations
- **Python 3.12**

## 📁 Contenu du repo

| Fichier | Description |
|---------|-------------|
| `Project_Steam_part1.ipynb` | Notebook complet — EDA avec PySpark |
| `projet_steam.pptx` | Présentation 9 slides |

## 🔗 Notebook Databricks

[👉 Accéder au notebook sur Databricks](https://dbc-37acc9cf-934c.cloud.databricks.com/editor/notebooks/2459004755100330?o=7474651101519635)

---
*Projet réalisé dans le cadre de la certification CDSD Jedha Bootcamp*
