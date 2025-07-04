# Ames House Price Prediction

## Project Overview

This project predicts house prices for Ames, Iowa, using advanced machine learning techniques. It leverages an XGBoost model trained on enriched features, including engineered features like total square footage, age, and combined bath counts.

---

## Features

**Data Cleaning & EDA**
- Missing value handling
- Exploratory analysis with seaborn/matplotlib
- Outlier inspection

**Feature Engineering**
- Numeric features (Lot Area, Gr Liv Area, etc.)
- Categorical features (Neighborhood, House Style, Sale Condition, etc.)
- Engineered features:
  - HouseAge
  - RemodAge
  - TotalBaths
  - TotalSF
  - Quality x Living Area interaction

**Machine Learning**
- Random Forest baseline
- Hyperparameter tuning with GridSearchCV
- XGBoost regressor with tuned parameters
- Log transformations tested

**Model Performance**
- Random Forest tuned: RMSE ≈ \$27,900, R² ≈ 0.89
- XGBoost tuned: RMSE ≈ \$23,300, R² ≈ 0.92

---
