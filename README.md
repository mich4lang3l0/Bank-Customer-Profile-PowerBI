# 💳 Bank Customer Profile Analysis | Power BI



## 📌 Project Overview

This project focuses on analyzing customer profile for a financial institution.


### 🔹 Key Metrics

- **Dataset:** Over 10 thousand of customer records (Anonymized).

- **Tool:** Power BI (Data Cleaning, Modeling, DAX, Visualization).



## 📊 Dashboard Gallery

*Since the live report cannot be published due to administrative restrictions, below are the high-resolution previews of the dashboard pages.*



### 1. Executive Summary

**Goal:** Take a deep look into customer overview

(images/customer_overview.png)
<img width="1597" height="910" alt="customer_overview" src="https://github.com/user-attachments/assets/33a2688f-ab14-4b26-98cf-b261dec648f6" />


### 2. Demographics

**Goal:** Deep dive into the demographics of customers.

(images/demographics.png)
<img width="1598" height="909" alt="demographics" src="https://github.com/user-attachments/assets/b1199f0a-e68d-44a7-aa6d-f9294aa852e2" />




### 3. Financial factors

**Goal:** Analyze Income and which factors have impact on it.

(images/financial_data.png)
<img width="1596" height="908" alt="income_analysis" src="https://github.com/user-attachments/assets/7ed49100-2155-4e65-b854-7216a6c17945" />




## 🛠️ Process & Technical Details



### 1. Data Transformation (Power Query)

- **Data Standardization:** Corrected data types for proper calculation.
- **Data Mapping:** Transformed categorical values (e.g., mapped '0/1' to 'Male/Female') to improve readability.



### 2. Data Modeling & DAX Measures

- Built a Star Schema data model.

- Created complex DAX measures, including:

  - **Average Customer Age** = `AVERAGE('Credit_cards'[Age])`

  - **Total number of Customers** `COUNT('Credit_cards'[ID])`

  - **Average Income for Customer** `AVERAGE(Credit_cards[Total_income])`



## 🚀 Key Insights & Recommendations

Based on the analysis, the following trends were observed:

1.  **Education vs. Income:** A strong positive correlation exists between education level and average income.
2.  **Age Structure:** The majority of customers fall into the middle-aged category (40-50 years old), representing the most financially active segment.
3.  **Marital Status:** Married customers constitute the largest segment of the bank's portfolio.



## 📂 Files in this Repository

- `Credit_cards_raport.pbix` - The Power BI source file.

- `Credit_cards_raport.pdf` - Full static export of the report.

Created by Michał Węglorz
