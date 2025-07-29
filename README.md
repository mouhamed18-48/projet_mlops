# 🍽️ Prévisions de revenus des restaurants - Pipeline MLOps

Ce projet vise à prédire le **revenu des restaurants** à l'aide de plusieurs modèles de Machine Learning, tout en intégrant une approche **MLOps avec Jenkins, MLflow, et Git**.

---
## 📁 Structure du projet

- PROJET MLOPS/
  - data/
    - train.csv                : Données brutes d'entraînement
    - test.csv                 : Données brutes de test

  - training_data/
    - train_transformed.csv    : Données d'entraînement transformées
    - test_transformed.csv     : Données de test transformées

  - notebooks/
    - resto_revenue_01_analyse.ipynb  : Notebook d’analyse exploratoire
    - resto_revenue_02_model.ipynb    : Notebook de modélisation
    - mlops_tasks.ipynb               : Tâches MLOps avec MLflow
    - best_model/                     : Dossier du meilleur modèle exporté
    - mlruns/                         : Répertoire de logs MLflow

  - jenkinsfile                       : Script de pipeline CI/CD pour Jenkins
  - mlopscicd.drawio.png             : Diagramme de l’architecture MLOps
  - README.md                        : Fichier de documentation


