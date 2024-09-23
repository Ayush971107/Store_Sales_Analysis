# Sales Forecasting and Exploratory Data Analysis (EDA)

This repository contains two primary components:

## 1. Exploratory Data Analysis (EDA)
- **File**: `SIF_EDA.ipynb`
- This notebook explores the **dataset** by merging sales data with economic indicators and markdown details. The analysis focuses on identifying patterns, seasonal trends, and key drivers of sales performance.
  
  **Key sections include:**
  - Correlation analysis between **markdowns**, **economic factors**, and **weekly sales**.
  - **Fourier and wavelet analysis** to uncover hidden cyclical patterns in sales.
  - **Promotion lift** analysis to quantify the effects of markdown strategies before, during, and after promotions.

## 2. Machine Learning for Sales Forecasting
- **File**: `SIF_ML.py`
- This script builds a **XGBoost Regressor model** to **forecast sales** using features such as markdowns, economic indicators (e.g., fuel price, unemployment), and store-specific characteristics.
- The model is trained on historical sales data and used to predict future sales, aiming for high accuracy in **forecasting weekly sales**.

## 3. Test Predictions
- **File**: `test_predictions.csv`
- This file contains the **predictions** made by the machine learning model on the test dataset, providing insights into expected sales for the corresponding weeks and stores.

---


