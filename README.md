# 🏦 Bank Loan & Credit Risk Analysis

## 📌 Project Overview

The **Bank Loan & Credit Risk Analysis** project focuses on analyzing loan applications, customer profiles, loan performance, and default risk to generate meaningful business insights.

The objective is to understand loan portfolio performance, identify customer segments with higher default rates, and help financial institutions make better lending and risk-management decisions.

This project uses a combination of Excel, SQL, Python, and Power BI to perform end-to-end data analysis.

## 🎯 Business Objectives

- Analyze overall loan application and approval performance.
- Calculate loan approval and default rates.
- Identify customer segments with higher default risk.
- Analyze the relationship between credit scores, income, age, and loan defaults.
- Evaluate outstanding loan amounts.
- Develop an interactive dashboard for business insights.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, validation, pivot tables and initial analysis |
| MySQL | Data querying and business analysis |
| Python | Data analysis, calculations and visualization |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Power BI | Interactive dashboard and KPI reporting |

## 📊 Dataset Information

- Total Records: 20,000
- Total Columns: 26
- Dataset Type: Loan and customer information
- Data includes customer demographics, employment details, credit scores, loan amounts, interest rates, repayment status and default information.

## 🔍 Project Workflow

### 1. Excel – Data Cleaning & Analysis
- Checked missing values and duplicate loan IDs.
- Validated data types and numerical values.
- Identified inconsistencies in loan approval and loan status.
- Created pivot tables for customer segmentation and default analysis.
- Developed an initial Excel dashboard.

### 2. SQL – Data Analysis
- Analyzed loan application and approval statistics.
- Calculated default rates across customer segments.
- Used aggregate functions, CASE statements, CTEs and window functions.
- Analyzed loan performance by credit score, income, employment type and loan purpose.

### 3. Python – Exploratory Data Analysis
- Loaded and analyzed the loan dataset using Pandas and NumPy.
- Calculated portfolio KPIs.
- Analyzed defaults by customer and loan characteristics.
- Examined correlations between numerical variables.
- Created visualizations using Matplotlib and Seaborn.

### 4. Power BI – Interactive Dashboard
Created an interactive dashboard containing 6 KPI cards and 6 analytical charts.

**Key KPIs:**
- Total Applications
- Approved Loans
- Approval Rate
- Default Rate
- Total Approved Loan Amount
- Total Outstanding Amount

**Dashboard Charts:**
1. Default Rate by Credit Score
2. Default Rate by Employment Type
3. Default Rate by Loan Purpose
4. Default Rate by Debt-to-Income Ratio
5. Default Rate by Age Group
6. Approved Loan Status Distribution

## 📈 Key Business Insights

- A total of 20,000 loan applications were analyzed.
- 7,973 applications were approved, representing an approval rate of 39.87%.
- The approved-loan default rate was approximately 29.11%.
- The total approved loan amount was approximately ₹597.53 crore.
- The outstanding loan amount was approximately ₹72.75 crore.
- Customers with different credit score segments showed different default patterns.
- Self-employed customers had a higher default rate than salaried customers in this dataset.
- Loan purpose and debt-to-income ratio also showed variations in default rates.

## ⚠️ Data Quality Observation

The dataset contained 12,027 records where rejected applications had a loan status of Current.

These records were retained rather than deleted. Loan performance and default-rate calculations were restricted to approved loans to avoid misleading results.

## 💡 Business Recommendations

- Strengthen credit risk assessment before loan approval.
- Monitor customer credit scores and debt-to-income ratios.
- Regularly track outstanding loan balances.
- Review customer segments with comparatively higher default rates.
- Investigate inconsistent application and loan status records before using operational data for decision-making.

## 🚀 Conclusion

This project demonstrates an end-to-end data analytics workflow, from data cleaning and SQL analysis to Python-based exploration and interactive Power BI reporting.

It showcases practical skills in data analysis, business intelligence, data visualization, and risk assessment.

---


**Domain:** Banking & Financial Analytics  
**Tools:** Excel | SQL | Python | Power BI
