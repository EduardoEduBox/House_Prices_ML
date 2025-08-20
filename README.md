# 🏠 House Prices Prediction – Kaggle Competition

This project is part of a Machine Learning course, using the **Ames Housing dataset** (Kaggle competition: [House Prices – Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)).

## 📌 Project Overview

The goal is to build an end-to-end machine learning pipeline to predict home sale prices.  
We follow the standard ML workflow:

1. Problem definition
2. Data cleaning & preprocessing
3. Feature engineering & encoding
4. Model training & evaluation
5. Kaggle submission

## ✅ Current Progress

- Created project repository with structured folders (`data/`, `notebooks/`, `src/`, `reports/`).
- Performed **data cleaning**:
  - Handled missing values with logical strategies (median, mode, None, 0).
  - Applied categorical fixes where NA = "None".
  - Ensured both **train** and **test** datasets have **0 missing values**.
- Generated cleaned datasets:
  - `train_clean.csv`
  - `test_clean.csv`

## 📂 Repository Structure

```
project/
├── data/        # Raw and processed datasets
├── notebooks/   # Jupyter notebooks (EDA, cleaning, modeling)
├── src/         # Reusable functions and scripts
├── reports/     # Figures and results
└── README.md
```

## 🚀 Next Steps

- Encode categorical features (ordinal mappings + one-hot).
- Build baseline models (Linear Regression, Random Forest, etc.).
- Evaluate with cross-validation and create the first Kaggle submission.
