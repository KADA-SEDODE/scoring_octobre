###### Projet de Scoring

## Auteurs : 
    Samanta Lamour
    Alexis Christien
    Issame Abdeljalil
    Marvin Kada-Sedode

## Projet ##

Ce projet a pour but de créer une grille de score sur une base d'individus ayant contracté des prêts banquaire. 
Il comporte la mise en place d’une EDA puis le développement de différents modèles : régression logistique, 
XGBoost, LigthGBM et Random Forest.

## Pré-requis ##

# Sous Windows #

Pour lancer le projet, il faut d'abord
  # Se placer via le terminal dans le dossier Projet_Scoring
  # Taper "virtualenv .venv" afin de créer un environnement virtuel
  # Taper ".venv\Scripts\activate" afin d'activer l'environnement
  # Taper "pip install -r requirements.txt" pour installer tout les packages nécessaires

# Sous Mac #

Pour lancer le projet, il faut d'abord
  # Se placer via le terminal dans le dossier Projet_Scoring_ToExport
  # Taper "virtualenv .venv" afin de créer un environnement virtuel
  # Taper "source .venv/bin/activate" afin d'activer l'environnement
  # Taper "pip install -r requirements.txt" pour installer tout les packages nécessaires


Ensuite, il faut lancer en premier lieu le Notebook EDA avant de lancer les Notebooks des modèles respectifs.
 
## Structure du projet ##

  # data : Comporte l’ensemble des données nécessaire au projet : La base intiale, les bases train et test pour le modèle de régression logistique et les bases train et test pour les autres modèles de Machine Learning
  # EDA.ipynb : Notebook contenant les étapes de Pre-Processing des données
  # Reg_Logi.ipynb : Notebook contenant le modèle de régression de logistique et la grille de score
  # XGBoost.ipynb : Notebook contenant le modèle de XGBoost
  # LightGBM : Notebook contenant le modèle de LightGBM
  # Random_Forest : Notebook contenant le modèle de Random Forest

######################################
