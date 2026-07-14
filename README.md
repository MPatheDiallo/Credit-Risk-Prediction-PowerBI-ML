# 📊 Prédiction du Risque de Défaut de Crédit avec Power BI et Machine Learning

![Power BI](https://img.shields.io/badge/Power%20BI-Analysis-F2C811?logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Classification-green)

# 📌 Présentation du projet

Les établissements financiers doivent être capables d'identifier les emprunteurs présentant un risque élevé de défaut afin de limiter les pertes financières et d'améliorer leurs décisions d'octroi de crédit.

Ce projet propose une solution complète d'analyse et de prédiction du risque de défaut en combinant **Power BI** pour la visualisation des données et **Python** pour le développement de modèles de Machine Learning.

L'objectif est de construire un tableau de bord interactif permettant :

- d'analyser le profil des emprunteurs ;
- d'identifier les principaux facteurs de risque ;
- de segmenter le portefeuille de crédit ;
- de comparer plusieurs modèles de Machine Learning ;
- de prédire la probabilité de défaut de chaque client ;
- d'aider à la prise de décision grâce à des indicateurs visuels.

  # 🎯 Objectifs

Les objectifs de ce projet sont :

- Réaliser une analyse exploratoire du portefeuille de crédit.
- Identifier les variables influençant le défaut de paiement.
- Segmenter les clients selon leur niveau de risque.
- Développer plusieurs modèles de Machine Learning.
- Comparer les performances des modèles.
- Intégrer les prédictions dans un tableau de bord Power BI.
- Fournir un outil d'aide à la décision destiné aux établissements financiers.
  
# 🛠️ Technologies utilisées

| Technologie | Utilisation |
|-------------|-------------|
| Python | Préparation des données et Machine Learning |
| Pandas | Manipulation des données |
| NumPy | Calcul scientifique |
| Scikit-learn | Régression Logistique et Random Forest |
| XGBoost | Modèle prédictif |
| Power BI | Visualisation et reporting |
| DAX | Création des KPI |
| Power Query | Transformation des données |

# 📂 Structure du projet

```text
Credit-Risk-Prediction-PowerBI-ML
│
├── data
├── images
├── powerbi
├── python
├── README.md
├── requirements.txt
└── LICENSE
```

# 📈 Tableau de bord Power BI

Le tableau de bord a été conçu pour fournir une vision complète du portefeuille de crédit, depuis l'analyse descriptive jusqu'à la prédiction du risque de défaut grâce au Machine Learning.

Il est composé de six pages interactives permettant d'analyser les emprunteurs, d'identifier les facteurs de risque et de faciliter la prise de décision.

## 📊 1. Executive Overview

Cette page présente une vue globale du portefeuille de crédit à travers les principaux indicateurs :

- Nombre total de clients
- Limite totale de crédit
- Nombre de clients en défaut
- Taux de défaut
- Âge moyen des emprunteurs
- Limite moyenne de crédit

Elle permet d'obtenir rapidement une vision synthétique de l'état du portefeuille.

![overview](images/overview.jpg)
