# Walmart Store Sales Forecasting

This project analyzes and forecasts retail sales using historical data from the Walmart Recruiting Store Sales Forecasting competition. Built as a final project for DATA602 (Machine Learning) in the UMBC Data Science MPS program, the goal was to apply regression modeling techniques to real-world retail data.

---

## 🔍 Problem Statement

Retail sales are highly seasonal and impacted by events such as holidays, promotions, and regional behavior. The goal of this project was to predict weekly sales for Walmart stores using historical sales, promotional markdowns, and store-specific features.

---

## 📈 Data Overview

The dataset includes:

* **train.csv:** historical sales data for each store and department
* **stores.csv:** metadata about store type and size
* **features.csv:** additional data such as temperature, fuel price, and holiday flags

These datasets were merged and enriched with engineered time-based features (e.g., week, month, holiday indicators).

---

## 📊 Methods & Models

* Exploratory Data Analysis (EDA) with `pandas`, `matplotlib`, and `seaborn`
* Feature engineering from raw date and categorical fields
* Forecasting using:

  * Linear Regression
  * Decision Trees
  * Random Forest
  * XGBoost (optional/final model)
* Evaluation using RMSE and R󟿼

---

## 🚀 Key Learnings

* Data preprocessing and proper feature engineering significantly impact model performance
* Holidays and store type had high feature importance across most models
* Tree-based models outperformed linear models on RMSE

---

## 📁 Repo Structure

```
walmart-sales-forecasting/
├── notebooks/
│   └── DATA602_Final_Clean.ipynb      # Final project notebook
├── data/                                  # (Optional if shared)
├── thumbnail.png                          # GitHub/LinkedIn visual
└── README.md
```

---

## 📇 Credits

Final project for DATA602: Machine Learning
University of Maryland, Baltimore County (UMBC) – MPS in Data Science
Author: Craig Drohan
