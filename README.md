# 🏋️‍♂️ Kaggle Playground Series S5E5 - Calorie Burn Prediction

This repository contains my solution for the Kaggle Playground Series - Season 5, Episode 5 competition, focused on predicting calorie expenditure based on biometric and activity data.

## 🏆 Competition Summary

- **Competition**: [Kaggle Playground Series - S5E5](https://www.kaggle.com/competitions/playground-series-s5e5/overview)
- **Goal**: Predict calories burned using features like height, weight, heart rate, duration, and temperature
- **Rank**: 682 / 4316
- **Top**: 💯 Top 16%

## 📂 Files

- `calorie prediction.ipynb`: Final notebook used for training and prediction. Includes:
  - Feature engineering
  - Model stacking (CatBoost, LightGBM, XGBoost)
  - Hyperparameter tuning
  - Final submission logic

## 🚀 Model Highlights

- Custom feature engineering (`BMR`, `HR_Temp_Interaction`, etc.)
- Ensemble of 3 models with Ridge as meta-learner
- Optimized for low RMSLE

## 📈 Evaluation Metric
- Root Mean Squared Logarithmic Error (RMSLE)

## 🧠 Tools & Libraries
- Python, Scikit-learn, CatBoost, XGBoost, LightGBM, NumPy, Pandas

---

Thanks for checking this out! ⭐
