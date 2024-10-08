# Projet de Machine Learning - Prédiction avec plusieurs algorithmes 

Ce projet à pour objectif de prédire la concentration en C02 en utilisant une vingtaine d'autres variables.

## Étapes du projet

1. **Exploration des données** : 
   - Analyse et visualisation des données pour mieux comprendre la distribution, les corrélations et les anomalies.
   
2. **Prétraitement des données** :
   - Nettoyage des données (gestion des valeurs manquantes, normalisation, suppression de variables redondantes ...)
   - Transformation des variables qualitatives en variables quantitatives.
   - Réduction de la dimension (ACP).

4. **Modélisation** :
   - Plusieurs algorithmes de machine learning ont été testés, tels que :
     - Régression linéaire
     - Forêts aléatoires (CART et Random Forest)
     - Support Vector Machines (SVM)
     - Réseaux de neurones
     - Boosting
   - Optimisation des hyperparamètres pour améliorer les performances.

5. **Évaluation** :
   - Les modèles ont été évalués avec des métriques comme l'accuracy, le RMSE (Root Mean Square Error) et la matrice de confusion.
  
6. **Complétion des valeurs manquantes** :
   - Utilisation des algorithmes MissForest et Amelia II pour compléter les valeurs manquantes et retester la précision de la prédiction.
   
## Résultats

Le modèle qui a donné les meilleurs résultats est Random Forest. La complétion des valeurs manquantes n'a pas donné d'amélioration significative dans la précision. Les variables les plus significatives dans la prédiction sont la part d'énergie renouvelables dans la consommation d'énergie d'un pays, la taille du pays, et la part d'énergie nucléaire.

