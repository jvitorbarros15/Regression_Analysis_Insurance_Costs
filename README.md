# Predicting Insurance Charges Using Regression Models

## 📌 Project Overview

This project aims to predict **individual medical insurance charges** based on personal and lifestyle attributes using machine learning regression models. It covers all key steps in a typical data science workflow — from data cleaning and visualization to model comparison and evaluation.

---

## 📊 Dataset

- **Source:** [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Rows:** 1338 individuals
- **Features:**
  - `age`: Age of the individual
  - `sex`: Gender
  - `bmi`: Body mass index
  - `children`: Number of children
  - `smoker`: Smoking status
  - `region`: Residential area in the US
  - `charges`: Medical insurance cost (target variable)

---

## ⚙️ Models Used

The following regression models were trained and evaluated:

- Linear Regression
- Polynomial Regression (degree 2)
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- XGBoost Regressor

---

## 📈 Evaluation Metrics

Each model was evaluated using the following metrics:

- **R² Score:** How well the model explains the variance in charges
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**

---

## 🏆 Best Performing Model

| Model                     | R² Score | MSE           | MAE         |
|--------------------------|----------|---------------|-------------|
| **XGBoost Regressor**     | 0.8684   | 2.04e+07      | 2475.34     |
| Polynomial Regression (d=2) | 0.8678   | 2.05e+07      | 2730.31     |
| Random Forest             | 0.8635   | 2.11e+07      | 2531.76     |

**XGBoost** performed the best in terms of R² and error metrics.

---

## 🧠 Key Takeaways

- **Smoking** is the strongest predictor of higher insurance charges.
- **Ensemble methods** (Random Forest, XGBoost) consistently outperform basic linear models.
- **Polynomial regression** can significantly boost performance on non-linear patterns.
- Scaling and proper encoding are essential for optimal model performance.

---

## 🧪 How to Run

> ⚠️ Requires Python 3.x and the following libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`.

