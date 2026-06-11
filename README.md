# Audit Data Complet d'une Marketplace E-commerce

## Contexte du projet
Ce projet a été réalisé dans le cadre du module **Traitement de Données**. L'objectif est d'analyser l'activité de la marketplace brésilienne **Olist** afin d'en tirer des recommandations business concrètes à partir d'indicateurs fiables.

L'analyse porte sur environ 100 000 commandes réalisées entre 2016 et 2018.

## Objectifs
- Analyser la satisfaction des clients.
- Évaluer les délais de livraison et identifier les retards.
- Mesurer la performance des vendeurs.
- Étudier la rentabilité des catégories de produits.

## Structure du projet
- `project_notebook.ipynb` : notebook principal d'analyse.
- `data/raw/` : jeux de données Olist bruts.
- `data/processed/` : tables préparées ou exportées, dont `df_final.csv`.
- `reports/figures/` : graphiques et schémas générés par le notebook.

## Technologies utilisées
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
Le dataset utilisé est disponible publiquement sur Kaggle : Brazilian E-Commerce Public Dataset by Olist.

## Installation
1. Clonez ce dépôt.
2. Installez les dépendances nécessaires :
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Laissez les fichiers CSV dans `data/raw/`, puis lancez `project_notebook.ipynb`.
