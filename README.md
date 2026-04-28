# 📊 Loan Default Analysis – Power BI Project

### Dashboard Link : https://app.powerbi.com/groups/752d8957-902b-4ac1-848f-892e7b25eb09/reports/38d07422-0acc-4e26-92a0-1d26cad556a2/95c44e66a7917f43cb74?experience=power-bi

## 🔍 Problem Statement
Financial institutions often struggle to accurately assess borrower risk, leading to loan defaults and financial losses. Identifying high-risk borrowers and understanding the factors influencing default behavior is critical for improving lending decisions.

This project focuses on analyzing borrower demographics, financial attributes, and loan characteristics to uncover patterns in loan defaults. The goal is to build an interactive Power BI dashboard that enables data-driven insights into credit risk and loan performance.

---

## 🎯 Objectives
- Analyze borrower profiles (Age, Income, Employment, Education)
- Identify key factors contributing to loan defaults
- Track Year-over-Year (YoY) trends in loan amounts and defaults
- Evaluate financial risk using Credit Score and DTI Ratio
- Provide actionable insights for better credit decision-making

---

## 📁 Dataset Information
- **File:** Dataset in CSV format named as `Loan_default.csv`
- **Source:** Imported using SQL Server (SSMS) & Power BI Dataflows

### Key Features:
- Borrower Demographics: Age, Marital Status, Education
- Financial Metrics: Income, Credit Score, DTI Ratio
- Loan Details: Loan Amount, Interest Rate, Loan Term
- Risk Indicators: Default, Co-signer, Mortgage, Dependents

---

## ⚙️ Data Processing
- Data imported via **SQL Server Management Studio (SSMS)**
- Data transformation using **Power Query**
- Data modeling with calculated columns and relationships

---

## 🧮 Key DAX Measures
- Year extraction for time analysis
- Income Brackets (Low, Medium, High)
- Credit Score Bins (Very Low → High)
- Age Groups segmentation

### Advanced Metrics:
- YoY Loan Amount Change (%)
- YoY Default Rate Change (%)
- YTD Loan Amount
- Default Rate by Year & Employment Type
- Median Loan Amount by Credit Score
- Average Loan by Age Group

---

## 📊 Dashboard Overview

### 1. Loan Overview
- Loan Amount by Purpose
- Default Rate by Employment Type
- Average Loan Amount by Age Group

### 2. Applicant Profile
- Loan Distribution by Credit Score
- Loans by Education Level
- Demographic Segmentation

### 3. Risk Metrics
- YoY Loan Trends
- YoY Default Changes
- YTD Loan Analysis
- Income & Employment Insights

---

## 📈 Key Insights
- Default rates remain stable (~11–12%) across years
- Higher credit scores indicate lower risk
- Employment type impacts default probability
- Majority of loans are issued to high-income individuals
- Adults and middle-aged groups contribute most to loan volume

---

## 🛠 Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- SQL Server (SSMS)
- Power BI Dataflows

---

## 🚀 Conclusion
This project showcases how business intelligence tools like Power BI can be used to analyze financial risk and loan performance. The dashboard enables stakeholders to make informed decisions by providing deep insights into borrower behavior and default patterns.

---

## 📸 Screenshots

![Snap_1](https://github.com/siddhant25201/loan-default-analysis-powerbi/blob/ce2f290a70401618a8fa38a2f5d91834e0344ce6/images/Loan-overview.png)

![Snap_2](https://github.com/siddhant25201/loan-default-analysis-powerbi/blob/ce2f290a70401618a8fa38a2f5d91834e0344ce6/images/Applicant-profile.png)

![Snap_3](https://github.com/siddhant25201/loan-default-analysis-powerbi/blob/ce2f290a70401618a8fa38a2f5d91834e0344ce6/images/Risk-metrics.png)

---

## 📌 Author
Siddhant Sharma
