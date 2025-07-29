# 🍽️ Restaurant Revenue Forecasting - MLOps Pipeline

Ce projet vise à prédire le **revenu des restaurants** à l'aide de plusieurs modèles de Machine Learning, tout en intégrant une approche **MLOps avec Jenkins, MLflow, et Git**.

---

## 📁 Structure du projet
PROJET MLOPS
├── data/ # Données brutes
│ ├── test.csv
│ └── train.csv
│
├── training_data/ # Données transformées
│ ├── test_transformed.csv
│ └── train_transformed.csv
│
├── notebooks/
│ ├── resto_revenue_01_analyse.ipynb # Analyse exploratoire des données
│ ├── resto_revenue_02_model.ipynb # Modélisation initiale (optionnel)
│ ├── mlops_tasks.ipynb # Pipeline d'entraînement, sélection, et log MLflow
│ ├── best_model/ # Dossier du meilleur modèle entraîné
│ └── mlruns/ # Logs MLflow des expériences
│
├── jenkinsfile # Pipeline Jenkins (CI/CD)
├── mlopscicd.drawio.png # Schéma de l'architecture MLOps
└── README.md # Fichier d'explication du projet
