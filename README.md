![CAT_DOG](img/cat_dog.jpeg)

Ce projet propose un défi pédagogique en **Deep Learning** visant à entraîner un modèle de classification d'images pour distinguer des photos de **chats** et de **chiens**.  
Il est conçu pour les apprenants souhaitant mettre en pratique les concepts fondamentaux du Deep Learning appliqués à la vision par ordinateur.

## Objectifs pédagogiques

- Comprendre les étapes de prétraitement des données d'images  
- Apprendre à construire et entraîner un modèle de classification d'images  
- Évaluer les performances du modèle sur des données de test  
- Explorer les techniques d'amélioration des performances du modèle  

## Prérequis

- Python ≥ 3.10  
- Environnement Jupyter (ou autre IDE compatible)  
- Bibliothèques de Deep Learning (par exemple, TensorFlow ou PyTorch)  
- Connaissances en apprentissage automatique  

## Installation

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/Sengsathit/Teaching-DL_challenge_classification_dogs_cats.git
   cd Teaching-DL_challenge_classification_dogs_cats
   ```

2. Créez un environnement virtuel (optionnel mais recommandé) :

   ```bash
   python -m venv venv
   source venv/bin/activate  # ou .\venv\Scripts\activate sous Windows
   ```

3. Installez les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

4. Lancez le notebook :

   ```bash
   jupyter notebook
   ```

## Structure du projet

- `challenge_dogs_cats.ipynb` : notebook principal illustrant le processus de classification d'images  
- `data/` : dossier contenant les images de chats et de chiens pour l'entraînement et le test  
- `img/` : ressources visuelles pour la présentation  
- `requirements.txt` : liste des dépendances Python nécessaires  