# 🛒 Sales Insights Dashboard – Walmart Kaggle Dataset

This project analyzes Walmart's historical weekly sales data to uncover patterns, seasonal trends, and the impact of economic factors and holidays. It includes data cleaning, exploratory data analysis, predictive modeling, and an interactive Power BI dashboard.

---

## 🎯 Objective

- Analyze sales trends across time, stores, and seasons
- Evaluate impact of holidays and economic factors like CPI & unemployment
- Forecast weekly sales using machine learning models
- Create a visual dashboard for business stakeholders

---

## 🧰 Tools & Technologies

- **Python** (pandas, matplotlib, seaborn, scikit-learn)
- **Jupyter Notebook** for EDA and modeling
- **Power BI** for dashboarding
- **Dataset:** [Walmart Sales Forecasting Dataset](https://www.kaggle.com/datasets/yasserh/walmart-dataset)

---

## 📊 Exploratory Data Analysis Highlights

- **Sales spike** notably during **Christmas** and **Super Bowl**
- Top performing stores: **Store 20**, **Store 4**, **Store 14**
- **Unemployment Rate** shows slight negative correlation with sales (R = -0.106)
- General holiday flag (`Holiday_Flag`) alone doesn't boost sales significantly

---

## 🔮 Modeling & Forecasting

### 1. **Linear Regression**
- **R² Score (Single Split):** 0.927  
- **RMSE (Single Split):** $150,373.59  
- **Average RMSE (5-Fold CV):** $155,788.41  
> A strong baseline model. Performs well but slightly sensitive to data splits.

---

### 2. **Random Forest Regressor**
- **R² Score (Single Split):** 0.951  
- **RMSE (Single Split):** $124,048.14  
> Captures non-linear patterns better and improves both R² and RMSE.

---

## 📈 Power BI Dashboard

📍 Located in: `dashboard/sales_dashboard.pbix`

Includes:
- Sales by store, year, and month
- Filters for store/date
- Holiday performance overview

---

## 📁 Project Structure

