# rare-condition-prediction

End-to-end pipeline for predicting rare medical conditions using synthetic pharmacy and retail data. Built in under 4 days as part of CVS Health pre-internship preparation.

## 🔍 Overview

This project simulates a real-world ML pipeline to identify individuals who may have rare medical conditions—using only their purchase behavior. No personal health records were used.

## 📦 Features

- Full EDA on 5M+ synthetic records
- Demographic and behavioral feature engineering
- Class imbalance handling (stratified split, scale_pos_weight)
- Two ML models: Random Forest and XGBoost
- Model interpretability via SHAP (global and individual)
- Streamlit dashboard for interactive prediction

## 📊 Models Used

- ✅ RandomForestClassifier  
- ✅ XGBoostClassifier (final model)  
- Metrics: Accuracy, Precision, Recall, F1-score, ROC AUC

## 🧠 Key Insights

- Behavioral signals (e.g., product variety, purchase frequency) are stronger predictors than demographics
- SHAP confirmed model interpretability and fairness
- Streamlit app allows easy scenario testing

## 🚀 Streamlit App

Run locally with:

```bash
streamlit run streamlit_app.py
