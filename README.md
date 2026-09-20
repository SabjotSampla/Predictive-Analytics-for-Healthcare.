# 🏥 Predictive Analytics for Healthcare : Forecasting Patient Length of Stay in Urban Hospitals

## 📊 Forecasting Patient Length of Stay in Urban Hospitals

This project uses **Machine Learning and Data Science** to predict the number of days a patient is expected to stay in a hospital. It analyzes clinical, demographic, and admission-related data to support healthcare resource planning and decision-making.

## 🎯 Objectives

* 🧹 Clean and preprocess healthcare data
* 📊 Perform Exploratory Data Analysis (EDA)
* ⚙️ Apply feature engineering
* 🤖 Build and compare regression models
* 📏 Evaluate model performance using standard metrics
* 💡 Generate healthcare-related insights

## 🎯 Target Variable

**`lengthofstay`** — represents the number of days a patient stays in the hospital.

**Problem Type:** Regression

## 📂 Dataset

* **Records:** 61,680
* **Features:** 28
* **Target:** `lengthofstay`
* Includes clinical, demographic, admission, and hospital-related information.

## 🔄 Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
EDA & Visualization
      ↓
Feature Engineering
      ↓
Model Development
      ↓
Model Evaluation
      ↓
Insights & Recommendations
```

## 🤖 Models Used

* Linear Regression
* Gradient Boosting Regressor
* CatBoost Regressor

## 📏 Evaluation Metrics

* **MAE** – Mean Absolute Error
* **MSE** – Mean Squared Error
* **RMSE** – Root Mean Squared Error
* **R² Score** – Coefficient of Determination

## 🛠️ Technologies

🐍 Python | 🐼 Pandas | 🔢 NumPy | 📊 Matplotlib | 🎨 Seaborn | 🤖 Scikit-learn | 🐱 CatBoost | 📓 Google Colab

## 🔐 Data Leakage Prevention

The `discharged` feature was excluded because it contains post-outcome information that could lead to **data leakage**. The identifier `eid` was also excluded from model training.

## 🚀 Future Scope

* 🌐 Deploy the model as a web application/API
* 📊 Create an interactive healthcare dashboard
* 🏥 Validate the model on external hospital datasets
* 🔍 Add Explainable AI for prediction interpretation

## 👩‍💻 Project Focus

**Healthcare Analytics | Predictive Modelling | Machine Learning | Regression**

---

⭐ *An end-to-end machine learning project for predicting hospital length of stay.*

