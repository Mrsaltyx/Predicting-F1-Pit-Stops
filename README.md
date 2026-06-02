🏎️ Predicting F1 Pit Stops | Kaggle Tabular Playground
📋 Présentation du Projet

Ce projet est dédié à la compétition Kaggle Tabular Playground Series, centrée sur la prédiction de la durée ou de la stratégie des arrêts aux stands en Formule 1. L'objectif est de s'exercer sur des datasets synthétiques complexes qui imitent les comportements réels des écuries.

L'enjeu technique réside dans la capacité à extraire des signaux pertinents à partir de données tabulaires tout en optimisant le compromis entre performance du modèle et temps d'inférence.
🚀 Objectifs Techniques

    Feature Engineering : Création de variables métier liées à l'usure des pneumatiques, la dégradation de l'essence et les deltas de performance par tour.

    Modélisation : Comparaison de modèles de Gradient Boosting (XGBoost, LightGBM, CatBoost) et potentiellement d'approches de Deep Learning tabulaire.

    Optimisation : Recherche d'hyperparamètres via optimisation bayésienne (Optuna).

🛠️ Stack Technique

    Langage : Python

    Data Science : Pandas, NumPy, Scikit-learn

    Modèles : LightGBM, XGBoost

    Tracking : MLflow ou Weights & Biases (pour le suivi des expérimentations)

    Environnement : Docker (pour la reproductibilité)

📂 Structure du Répertoire
Plaintext

├── notebooks/          # Exploratory Data Analysis (EDA) & Prototypes
└── README.md

📈 Méthodologie

    EDA : Analyse de la distribution des données synthétiques et détection d'éventuels artefacts.

    Validation : Mise en place d'une stratégie de Cross-Validation robuste (Stratified K-Fold) pour éviter le surapprentissage.

    Ensembling : Utilisation de techniques de Stacking ou de Blending pour maximiser le score final.
