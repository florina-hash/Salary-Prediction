# Salary Prediction using LinearRegression

A simple machine learning project that predicts an employee's salary based on their years of experience using a Linear Regression model. 

## 📌 Project Overview
This project demonstrates a foundational approach to predictive modeling. It uses a small synthetic dataset of years of experience and corresponding salaries to train a Scikit-Learn `LinearRegression` model. The project includes data splitting, model training, prediction, evaluation, and data visualization.

## 📊 Dataset
The model is trained on a linear mapping of experience to salary:
* **Feature (X):** `Experience` (Years)
* **Target (y):** `Salary` ($)

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `pandas`, `matplotlib`, `scikit-learn`

## ⚙️ Model Performance
Because the underlying data has a perfectly linear relationship, the model achieves absolute precision:
* **Mean Squared Error (MSE):** `~0.0` ($1.98 \times 10^{-23}$)
* **$R^2$ Score:** `1.0` (100% variance explained)
