# Audit Data Complet d'une Marketplace E-commerce

## Contexte du projet
Ce projet a été réalisé dans le cadre du module **Traitement de Données**. L'objectif est de mener une analyse approfondie de l'activité de la marketplace brésilienne **Olist** afin de proposer des recommandations business concrètes basées sur des indicateurs fiables.

L'analyse porte sur environ 100 000 commandes réalisées entre 2016 et 2018.

## Objectifs
- Analyser la satisfaction des clients.
- Évaluer les délais de livraison et identifier les retards.
- Mesurer la performance des vendeurs.
- Étudier la rentabilité des catégories de produits.

## Structure du projet
Le projet est structuré autour d'un notebook principal : `project_notebook.ipynb`.
Il suit une méthodologie en 5 étapes :
1. **Étape 1** : Chargement et exploration des données brutes.
2. **Étape 2** : Nettoyage rigoureux et construction de la table finale d'analyse.
3. **Étape 3** : Construction des indicateurs et analyse globale (CA, panier moyen, évolution mensuelle).
4. **Étape 4** : Analyses métier approfondies (Satisfaction, Logistique, Géographie).
5. **Étape 5** : Synthèse business et recommandations stratégiques.

## Technologies utilisées
- **Python 3**
- **Pandas** : Manipulation et analyse de données.
- **NumPy** : Calculs numériques.
- **Matplotlib** & **Seaborn** : Visualisation de données.

## Dataset
Le dataset utilisé est disponible publiquement sur Kaggle : Brazilian E-Commerce Public Dataset by Olist.

## Installation
1. Clonez ce dépôt.
2. Assurez-vous d'avoir installé les dépendances nécessaires :
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Placez les fichiers CSV d'Olist à la racine du projet et lancez le notebook.