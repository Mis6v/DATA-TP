# TP N°1 : Pipeline d'Acquisition de Données (KDD)

Ce projet a été réalisé dans le cadre du module Data Mining .

## Objectif du TP
L'objectif principal est de construire un pipeline d'acquisition de données capable de collecter et de fusionner des données provenant de sources hétérogènes :
- **CSV** : Données structurées sur la performance des étudiants.
- **JSON** : Données semi-structurées sur des films.
- **SQL** : Simulation d'extraction de données filtrées.
- **Web Scraping** : Extraction de titres depuis Wikipedia.

## Structure du Projet
- `data/` : Contient les fichiers sources (`student-mat.csv`, `movies.json`).
- `notebooks/` : Contient le notebook principal `TP1_KDD_Pipeline.ipynb`.
- `src/` : Dossier pour les scripts Python réutilisables.
- `requirements.txt` : Liste des dépendances Python.

## Installation
Pour exécuter ce projet, installez les dépendances nécessaires :
```bash
pip install -r requirements.txt
```

## Utilisation
Ouvrez le fichier `notebooks/TP1_KDD_Pipeline.ipynb` avec Jupyter Lab ou VS Code pour visualiser les étapes de l'acquisition et de la fusion des données.
