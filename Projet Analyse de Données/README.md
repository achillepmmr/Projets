# Projet d'Analyse de Données - Vélib (apprentissage non supervisé)

## Introduction

Ce projet porte sur l'analyse des données du service de vélos en libre-service **Vélib'** de la ville de Paris. L'objectif est de comprendre les tendances d'utilisation, les zones géographiques à forte demande et d'identifier les périodes de forte affluence. L'analyse est réalisée à partir de données ouvertes, comprenant des informations sur les stations : les disponibilités en temps réel, leur localisation GPS et leur altitude.

## Analyse des données

1. **Exploration des données** :
   - Importation et nettoyage des jeux de données (gestion des valeurs manquantes, conversion des dates, etc.).
   - Exploration des variables telles que les disponibilités en vélos, les types de vélos (mécaniques ou électriques), et les données géographiques des stations.
   - Création de nouveaux datasets plus pertinents avec moins de variables.

2. **Visualisation géographique** :
   - Utilisation de package (leaflet, ...) pour créer des cartes interactives montrant la répartition des stations Vélib' à travers Paris et les zones périphériques.
   - Identification des zones à forte concentration de stations et des zones sous-desservies.

3. **Réduction du nombre de variables** : 
   - Application d'ACP pour réduire la dimension et le nombre de variables

4. **Méthodes de clustering : 
   - KMeans, CAH, et Gaussian Mixture pour regrouper les stations similaires dans leur fréquentation.

## Résultats

Identification de zones géographiques dans Paris : des zones où le chargement des stations varient le matin et en soirée la semaine (zone d'habitation/travail), zones qui varient le week-end (zones festives), et des zones où le chargement varie peu (stations en altitude, en périphérie ...)


