# 💎 Diamond Price & Value Prediction with XGBoost

This project builds a machine learning pipeline that predicts diamond prices and evaluates their value-for-money score.

## 🚀 Project Workflow

- 📊 Exploratory Data Analysis (EDA)
- 🔧 Feature Engineering (OneHotEncoding)
- 📈 Model Training with XGBoost
- 🎯 Hyperparameter Optimization with Optuna
- 🧠 Model Explainability using SHAP
- 🗂️ Value Score Calculation: `Predicted / Actual`

## 📌 Main File: `diamond_price_pipeline.pkl`

You can load the model like this:

```python
import pickle
with open("diamond_price_pipeline.pkl", "rb") as f:
    pipeline = pickle.load(f)

predictions = pipeline.predict(X_new)

## 📂 Folders
├── data/ # Исходные данные
├── model/ # Jupyter-ноутбуки
├── model/ # Готовая модель
└── README.md # Описание проекта
