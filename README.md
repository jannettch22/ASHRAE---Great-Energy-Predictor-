# ASHRAE---Great-Energy-Predictor-
Cette répertoire contains mon travail à propos la compétition ASHRAE - Great Energy Predictor dont son objectif est de créer des modéles à base de l'apprentissage afin de prédire la consommation de l'éléctricité, de l'eau glacée, du vapeur ou de l'eau chaude d'un immeuble à une date et heure donnée.
Ce travail qui présenté dans le notebook ASHRAE2.ipynb se compose de ces phases:
  1. collection des données
  2. préparation des données
  3. modélisation
  4. prédiction.
  5. soumission.
  
Afin d'établir ce travail, nous avons recours à ces librairies là:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - keras
  - pickle

Dans la phase de modélisation, on a crée un modéle MLP ( Multi-Layer Perceptron ) 16 couches:
  - 6 couches Dense.
  - 5 couches Dropout.
  - 5 couches BatchNormlization
