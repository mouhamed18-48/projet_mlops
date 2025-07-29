# 🍽️ Prévisions de revenus des restaurants - Pipeline MLOps

Ce projet vise à prédire le **revenu des restaurants** à l'aide de plusieurs modèles de Machine Learning, tout en intégrant une approche **MLOps avec Jenkins, MLflow, et Git**.

---

<pre lang="markdown"> ## 📁 Structure du projet ``` PROJET MLOPS/ ├── data/ │ ├── train.csv # Données brutes d'entraînement │ └── test.csv # Données brutes de test │ ├── training_data/ │ ├── train_transformed.csv # Données transformées (train) │ └── test_transformed.csv # Données transformées (test) │ ├── notebooks/ │ ├── resto_revenue_01_analyse.ipynb # Analyse exploratoire │ ├── resto_revenue_02_model.ipynb # Modélisation initiale │ ├── mlops_tasks.ipynb # Pipeline MLflow & sélection modèle │ ├── best_model/ # Modèle retenu après sélection │ └── mlruns/ # Expérimentations MLflow (logs) │ ├── jenkinsfile # Pipeline Jenkins pour CI/CD ├── mlopscicd.drawio.png # Diagramme de l’architecture MLOps └── README.md # Explication du projet ``` </pre>

