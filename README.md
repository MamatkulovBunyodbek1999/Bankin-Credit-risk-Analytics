# 🏦 Credit Risk & Fraud Analysis

## 📌 Overview
This project analyzes banking loan data to evaluate credit risk and identify potential fraud patterns.

The goal is to simulate how financial institutions assess borrower risk, segment customers, and make data-driven lending decisions.

---

## 🎯 Objectives
- Analyze loan default behavior  
- Segment customers based on income and loan size  
- Identify high-risk borrower groups  
- Simulate fraud detection logic  
- Build a business-oriented dashboard for decision-making  

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy) – data cleaning & feature engineering  
- SQL (SQLite) – analytical queries  
- Power BI – dashboard & visualization  
- Jupyter Notebook / VS Code – development environment  

---

## 📂 Dataset
The dataset includes loan application data with features such as:
- Income  
- Loan Amount  
- Credit-related attributes  
- Default indicator (target variable)  

---

## ⚙️ Workflow

### 1. Data Preparation
- Cleaned raw dataset using Pandas  
- Standardized column names  
- Handled missing values  
- Created new features:
  - income_group  
  - loan_segment  
  - fraud_flag  

---

### 2. Credit Risk Analysis (SQL + Pandas)

Key analyses performed:
- Overall default rate  
- Risk by income segment  
- Risk by loan size  
- Multi-dimensional risk segmentation  

---

### 3. Fraud Detection Logic
Simulated fraud indicators based on abnormal patterns:
- Low income + high loan amount  
- Behavioral inconsistencies  

Created:
- fraud_flag (0 = normal, 1 = suspicious)

---

### 4. Dashboard (Power BI)

Developed an interactive dashboard including:
- Default Rate (KPI)  
- Total Loans  
- Fraud Cases  
- Risk by Income Group  
- Risk by Loan Segment  
- Fraud vs Non-Fraud comparison  

---

## 📊 Key Insights
- Lower income groups exhibit significantly higher default rates  
- Larger loan amounts correlate with increased risk exposure  
- Fraud-flagged cases show elevated probability of default  
- Risk is not uniform — strong segmentation patterns exist  

---

## 📁 Project Structure
