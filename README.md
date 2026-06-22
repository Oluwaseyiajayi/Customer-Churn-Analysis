# Customer-Churn-Analysis
Customer churn analysis using Python for customer retention

# Customer Churn Analysis Using Python

## Overview

Customer retention is a critical challenge in the telecommunications industry, as acquiring new customers is often more expensive than retaining existing ones. This project analyzes customer churn data to identify the factors that contribute to customer attrition and provides actionable insights that can help improve retention strategies and business performance.


---

## Business Problem

The company is experiencing customer churn, resulting in lost revenue and increased customer acquisition costs. The key business question addressed in this analysis is:

**"What factors contribute most to customer churn, and how can the company reduce customer churn?"**

By analyzing customer demographics, service subscriptions, contract types, payment methods, tenure, and billing information, this project identifies customer segments that are most at risk of leaving.

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer-level information including:

* Demographics
* Contract details
* Service subscriptions
* Payment methods
* Monthly charges
* Total charges
* Customer tenure
* Churn status

**Dataset Size:**

* 7,043 customer records
* 21 features

---

## Project Workflow

### 1. Data Collection

* Imported customer churn dataset from CSV format.
* Inspected dataset structure and data quality.

### 2. Data Cleaning

* Removed duplicate records.
* Converted data types where necessary.
* Handled missing values.
* Created a separate cleaned dataset (`clean_df`) for all subsequent analyses.

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Investigated churn distribution.
* Examined service usage patterns.
* Explored customer contract and payment behaviors.

### 4. Data Visualization

Created visualizations to identify trends and relationships, including:

* Churn distribution
* Contract type analysis
* Payment method analysis
* Monthly charges distribution
* Tenure distribution

### 6. Business Insight Generation

Translated analytical findings into actionable business recommendations aimed at improving customer retention.

---

## Key Findings

### Month-to-Month Contracts Drive Churn

Customers on month-to-month contracts exhibited significantly higher churn rates compared to customers on one-year and two-year contracts.

### New Customers Are More Likely to Leave

Customers with shorter tenure were substantially more likely to churn than long-term customers.

### Higher Monthly Charges Increase Churn Risk

Customers paying higher monthly fees showed a greater tendency to leave the service.

### Payment Method Influences Retention

Customers using electronic checks demonstrated higher churn rates compared to customers using automatic payment methods.

---

## Business Recommendations

Based on the analysis, the following recommendations can help reduce churn:

1. Encourage customers to migrate from month-to-month contracts to long-term plans through discounts and loyalty incentives.
2. Strengthen customer onboarding and engagement during the first few months of service.
3. Review pricing strategies for customers with high monthly charges.
4. Promote automatic payment methods to improve customer retention.
5. Develop targeted retention campaigns for high-risk customer segments.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
