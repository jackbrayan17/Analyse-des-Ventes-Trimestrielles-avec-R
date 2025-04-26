# Analyse des Ventes Trimestrielles

## Description

Ce projet analyse les ventes trimestrielles d'une entreprise sur une période de trois ans. L'objectif est de détecter la saisonnalité, estimer la tendance, extraire les composantes saisonnières, désaisonnaliser les données et reconstituer les valeurs attendues.

## Contenu du Projet

- **Création des Données** : Génération d'un tableau de données avec les ventes trimestrielles.
- **Série Temporelle** : Transformation des données en une série temporelle trimestrielle.
- **Visualisation** : Tracé des séries pour visualiser les ventes et la tendance.
- **Estimation de la Tendance** : Régression linéaire pour estimer la tendance des ventes.
- **Décomposition** : Extraction des composantes saisonnières et de tendance.
- **Désaisonnalisation** : Création d'une série désaisonnalisée.
- **Reconstitution des Valeurs Attendues** : Visualisation des valeurs observées et reconstituées.

## Prérequis

- R
- RStudio (facultatif)
- Packages : `dplyr`, `forecast`

## Installation des Paquets

Assurez-vous d'avoir les paquets nécessaires installés :

```r
install.packages("dplyr")
install.packages("forecast")
