# 🏡 Bangalore House Prices Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/ML-Regression-green.svg)
![Status](https://img.shields.io/badge/Project-Active-brightgreen.svg)

Predicting real-estate prices in Bangalore using Machine Learning.  
This project focuses on analyzing how different features influence housing prices and building an accurate predictive model.

---

## 📌 Project Overview
This project implements a full machine-learning pipeline to estimate house prices in Bangalore based on:
- Location
- BHK (bedrooms)
- Bathrooms
- Total square feet
- Price per square feet
- Other engineered features

It includes EDA, model training, evaluation, and deployment-ready prediction code.

---

## 📂 Dataset Description
The dataset includes the following columns:

| Feature | Description |
|--------|-------------|
| `location` | Area / locality of the property |
| `size` | Number of bedrooms (BHK) |
| `total_sqft` | Total built-up area |
| `bath` | Number of bathrooms |
| `balcony` | Number of balconies |
| `price` | Price of the property (target variable) |

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA covers:
- Price distribution
- BHK-wise price variations
- Area (sqft) vs price relationships
- Location-wise price patterns
- Outlier detection & removal
- Visualizations using Matplotlib & Seaborn

These help clean and transform the dataset for optimal model performance.

---

## 🛠️ Feature Engineering
Major transformations include:
- Converting `size` → numerical BHK
- Cleaning `total_sqft` (ranges, text values, outliers)
- Creating `price_per_sqft`
- Removing inconsistent entries and unrealistic properties
- One-hot encoding for location
- Dimensionality reduction

---

## 🤖 Machine Learning Models Used
The following models were tested and compared:
- Linear Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor

The best-performing model is saved using `pickle`.

---

## 📈 Model Performance
Metrics achieved:
- **R² Score:** ~0.85–0.90
- **MAE:** Low error range based on test samples
- **RMSE:** Improved significantly after outlier removal

Performance varies depending on dataset split and hyperparameters.

---


