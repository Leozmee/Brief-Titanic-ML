# Brief-Titanic-ML

## 1. Présentation du projet
Ce projet a pour objectif d'analyser les données des passagers du Titanic afin de comprendre quels facteurs ont influencé leurs chances de survie. L'analyse porte notamment sur le sexe, l'âge, la classe du billet et la composition familiale des passagers.

## 2. Objectifs
- Explorer et comprendre les données du Titanic.
- Identifier et traiter les valeurs manquantes.
- Nettoyer et préparer les données.
- Créer de nouvelles variables pour améliorer l'analyse.
- Construire et comparer plusieurs modèles de prédiction.

## 3. Outils utilisés
- Google Colab / Jupyter Notebook
- Bibliothèques Python : Pandas et NumPy / Matplotlib et Seaborn / Scikit-learn et XGBoost

## 4. Étapes du projet

#### A/ Exploration des données (EDA)
- Analyse des caractéristiques des passagers.
- Étude de la répartition des âges, des sexes et des classes.
- Analyse des taux de survie selon différents critères.

#### B/ Nettoyage et préparation
- Remplacement des âges manquants par la médiane.
- Remplacement des ports d'embarquement manquants par la valeur la plus fréquente.
- Suppression de certaines colonnes inutiles.
- Encodage des variables catégorielles.

#### C/ Création de nouvelles variables
- Titre : titre du passager (Mr, Mrs, Miss, Master, Rare).
- Taille de la famille
- indique si le passager voyage seul ou pas

#### D/ Modélisation
Trois modèles de classification ont été entraînés et comparés :
- Régression logistique
- Random Forest
- XGBoost

## 5. Résultats des modèles
Régression logistique  - Précision à 84,92 %

Random Forest          - Précision à 81,56 %

XGBoost                - Précision à 81,01 %

La régression logistique obtient le meilleur résultat sur les données de test, avec une précision de 84,92 %.

## 6. Source des données
Les données utilisées proviennent du jeu de données Titanic disponible sur Kaggle : 
- Utilité pour la description des variables
- Fichier Train disponible également
