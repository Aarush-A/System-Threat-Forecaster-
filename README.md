# 🛡️ System Threat Forecaster – Malware Detection with Telemetry Data

[![Kaggle Competition](https://img.shields.io/badge/View%20on-Kaggle-20BEFF?logo=kaggle)](https://www.kaggle.com/competitions/System-Threat-Forecaster/)

This repository contains my solution for the [System Threat Forecaster](https://www.kaggle.com/competitions/System-Threat-Forecaster/) Kaggle competition. The goal was to predict whether a machine would be infected by malware, based on 70+ telemetry features collected from antivirus threat reports.

---

## 📊 Problem Statement

> Predict a machine’s probability of malware infection using system-level attributes and antivirus configuration details.  
> Binary classification task with a target column indicating whether a machine was infected.

---

## 🧠 Highlights

- 📈 **Ranked 550 / 1500+ participants** with a leaderboard score of **0.62570** (top score: 0.69605)
- 🔍 Handled high-cardinality categorical features, missing values, and skewed class distribution
- 🧹 Feature engineering on date fields (`DateAS`, `DateOS`), processor attributes, and antivirus configurations
- ⚙️ Models used: **LightGBM**, **Random Forest**, baseline logistic regression
- 🧪 Evaluation: AUC-ROC, Confusion Matrix, Stratified Cross-validation

---

## 🗂️ Files

- `notebook.ipynb`: Full solution including preprocessing, EDA, feature engineering, model training and evaluation
- `train.csv`: Training data provided by Kaggle (not included due to size)
- `test.csv`: Test data provided by Kaggle (not included due to size)
- `sample_submission.csv`: Format for submission

---

## 🔧 Techniques Used

- Pandas, NumPy for preprocessing
- Seaborn, Matplotlib for visualization
- LightGBM, Scikit-learn for modeling
- StratifiedKFold for cross-validation

---

## 📎 Resources

- [Competition Link](https://www.kaggle.com/competitions/System-Threat-Forecaster/)

---

## 🚀 To Do

- [ ] Try deep learning with tabular models (e.g., TabNet or CatBoost)
- [ ] Add SHAP for model explainability
- [ ] Hyperparameter optimization with Optuna

---
