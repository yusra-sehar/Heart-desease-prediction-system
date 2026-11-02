# Heart-desease-prediction-system
Comparative machine learning study for cardiovascular disease risk prediction using the CDC BRFSS 2022 dataset.

# Cardiovascular Disease Prediction: Comparative ML Study

A machine learning project that compares multiple classification algorithms
for predicting cardiovascular disease (heart attack history) from health and
lifestyle data.

## Dataset
CDC BRFSS 2022 (about 320,000 records, 40 features)

Personal Key Indicators of Heart Disease (CDC BRFSS), by Kamil Pytlak, available on Kaggle:
https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

The target is self-reported heart disease / heart attack history, so this project
classifies existing disease status; it does not predict future disease.

## How to Run
1. Download the dataset CSV from the link above and place it in the project folder.
2. Install the libraries: pip install -r requirements.txt
3. Open the notebook and run all cells.

## What This Project Does
- Data preprocessing and feature engineering
- Class-imbalance handling using SMOTE
- Feature selection using ANOVA F-score
- Trains and compares linear, tree-based, boosting and ensemble models
- Evaluates models using precision, recall, F1-score, ROC-AUC and cross-validation

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn

## Status
Research paper in progress.
