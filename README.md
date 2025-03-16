# Rakuten_Multi-modal_Colour_Extraction

## Description

Ce projet est basé sur le challenge organisé par le Rakuten Institute of Technology (RIT), qui porte sur l'extraction automatique des couleurs des produits à partir de données multimodales, incluant des images et des textes provenant du catalogue de produits de la marketplace Rakuten Ichiba. L’objectif est d’améliorer la classification des attributs de couleur des produits, une tâche essentielle pour la recherche et la recommandation de produits sur la plateforme.

Les données sont particulièrement difficiles à traiter en raison de plusieurs facteurs, notamment des descriptions mal rédigées, des données manquantes ou bruitées, et un déséquilibre des classes, où certaines couleurs apparaissent plus fréquemment que d'autres. Le challenge implique environ 250 000 produits, avec des informations provenant d'images et de textes.

L'objectif principal du projet est de prédire les couleurs associées aux produits en utilisant une approche multimodale, combinant les informations des images, des titres et des descriptions. Étant un problème de classification multi-label, un produit peut être associé à plusieurs couleurs (par exemple, un sac rouge et noir).

## Prérequis

Pour utiliser ce projet, vous devez d'abord créer un environnement virtuel et installer les packages répertoriés dans le fichier `requirements.txt`.

## Installation

1. Cloner le dépôt sur votre machine :
   ```bash
   git clone https://github.com/votre-utilisateur/rakuten_Multi-modal_Colour_Extraction.git
   cd rakuten_Multi-modal_Colour_Extraction

2. Installer les dépendances avec pip
   ```bash
   pip install -r requirements.txt

## Structure des fichiers (a changer plus tard)
``` 
/Data             # Contient les jeux de données
    ├── train.csv  # Jeu de données d'entraînement
    └── test.csv   # Jeu de données de test
/Modèles_finaux   # Contient les deux modèles finaux
    ├── CatBoost_predictions.csv  # Modèle le plus performant
    └── XGboost_predictions.csv   # Second modèle le plus performant
/Notebook.ipynb      # Contient le notebook principal
/Présentation.pdf    # Contient le support de présentation
/README.md           # Ce fichier
/Requirements.txt    # Liste des dépendances Python
```
## Contributeurs

- **Salma BENMOUSSA**
- **Charlotte CEGARRA**

Ce projet a été développé dans le cadre du Master MOSEF, à l'université Paris 1 Panthéon Sorbonne.

## 📩 Contact

N'hésitez pas à nous contacter pour toute question :

- salmabenmoussa103@gmail.com 
- charlottecegarrapro@gmail.com
