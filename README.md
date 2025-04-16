# 🛒 Online Shopping Behavior Analysis

This project provides a comprehensive analysis of customer behavior on an e-commerce platform using transaction and demographic data. The main objective is to understand purchasing patterns and predict discount strategies using data science techniques.

## 🎯 Problem Statement

**Target Variable:** `Discount_pct`  
Analyze how customer and transaction features influence the discount applied during purchases.

## 📊 Dataset Summary

- **Rows:** 52,599  
- **Columns:** 21  
- **Key Features:**
  - CustomerID, Gender, Location, Tenure_Months  
  - Transaction_ID, Transaction_Date, Month  
  - Product_SKU, Product_Category, Product_Description  
  - Quantity, Avg_Price, Delivery_Charges, GST  
  - Coupon_Code, Coupon_Status, Online_Spend, Offline_Spend  
  - Discount_pct

## 🔍 Project Steps

1. **Data Cleaning:** Handled missing values, removed duplicates, and corrected data types.  
2. **Descriptive Statistics:** Summarized data distribution and key metrics.  
3. **Exploratory Data Analysis:**  
   - Visualized trends in spending, coupon usage, discounts, and product categories.  
   - Identified key influencers of discount percentage.  
4. **Correlation Analysis & Outlier Detection:** Used correlation matrices and box plots.  
5. **Feature Engineering:** Derived features like month, year, spend ratios, etc.  
6. **Data Scaling:** Standardized numeric features for model readiness.  
7. **Initial Modeling:** Built baseline regression models and tested hypotheses.  
8. **Documentation:** Summarized findings and insights.

## 📈 Power BI Dashboard

- Included `project.end___1.pbix` file with interactive visualizations:
  - Sales by region, gender, and time  
  - Online vs offline spend  
  - Product performance  
  - Coupon and discount impact

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)  
- Power BI


## ✅ Future Work

- Improve model accuracy with advanced ML algorithms  
- Deploy results with Streamlit/Flask  
- Automate data pipeline for real-time analytics


