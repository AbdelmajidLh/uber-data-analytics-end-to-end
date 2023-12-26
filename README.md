# Projet Uber Data Analytics - Pipeline End-to-End

Ce repository contient le code source et les artefacts associés au projet de data analytics Uber. L'objectif principal de ce projet est de créer un pipeline de bout en bout pour collecter, traiter et visualiser les données en utilisant les technologies suivantes : Python, MAGE, Mage VM, BigQuery, et Looker.

## Contenu du Repository

- **`src/`**: Le répertoire source contient le code Python pour l'ETL (Extract, Transform, Load) qui prend en charge la transformation des données brutes.
  
- **`mage/`**: Ce répertoire contient les configurations spécifiques à l'environnement MAGE et Mage VM pour faciliter le déploiement et l'exécution du pipeline ETL.

- **`sql/`**: Les scripts SQL utilisés pour créer et gérer les tables dans BigQuery.

- **`looker/`**: Configuration et rapports LookML pour la visualisation des données dans Looker.

- **`docs/`**: La documentation du projet, y compris des informations sur l'installation, l'utilisation du pipeline, et des explications sur la structure des données.

## Architecture du Pipeline

1. **Collecte des données brutes :** Les données brutes sont collectées à partir de [source de données] et stockées dans des fichiers.

2. **ETL avec Python dans MAGE VM :** Les données brutes sont traitées à l'aide d'un ETL basé sur Python exécuté dans l'environnement MAGE VM.

3. **Stockage dans BigQuery :** Les données transformées sont chargées dans BigQuery, servant de data warehouse pour l'analyse ultérieure.

4. **Visualisation avec Looker :** Les résultats de l'analyse sont visualisés à l'aide de Looker, offrant des tableaux de bord interactifs et des rapports.

## Prérequis

- Python 3.x
- MAGE et Mage VM configurés
- Compte BigQuery pour le stockage des données
- Accès à Looker pour la visualisation
