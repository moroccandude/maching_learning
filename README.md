# Prédiction de la présence d'un ascenseur dans les annonces immobilières

Ce projet implémente une série de modèles de classification afin de prédire la présence d'un ascenseur dans les annonces immobilières en fonction de diverses caractéristiques de l'annonce. La prédiction de la variable cible est réalisée via plusieurs modèles de machine learning, et la gestion du déséquilibre des classes est effectuée en utilisant la méthode SMOTE (Synthetic Minority Over-sampling Technique).

## Table des matières

- [Contexte et Objectif](#contexte-et-objectif)
- [Installation et Prérequis](#installation-et-prérequis)
- [Description des données](#description-des-données)
- [Prétraitement des données](#prétraitement-des-données)
- [Modèles et Évaluation](#modèles-et-évaluation)
- [Visualisations](#visualisations)
- [Améliorations possibles](#améliorations-possibles)

## Contexte et Objectif

L'objectif de ce projet est de prédire la présence d'un ascenseur (`has_elevator`) dans une annonce immobilière. La variable cible est une variable binaire indiquant la présence (1) ou l'absence (0) d'un ascenseur.

Les principales étapes du projet sont les suivantes :
1. Création de la variable cible `has_elevator` à partir des données des équipements.
2. Traitement du déséquilibre des classes en utilisant la méthode SMOTE.
3. Entraînement de modèles de classification.
4. Évaluation des performances des modèles.
5. Visualisation des résultats et des performances des modèles.

## Installation et Prérequis

Pour exécuter ce projet, vous devez avoir installé Python ainsi que les bibliothèques suivantes :
- pandas
- numpy
- scikit-learn
- imbalanced-learn (pour SMOTE)
- seaborn
- matplotlib

### Installation des dépendances

```bash
pip install pandas numpy scikit-learn imbalanced-learn seaborn matplotlib
