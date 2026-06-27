# AI-Powered Loan Portfolio Analytics & Risk Prediction

An end-to-end Data Analytics and Machine Learning project that analyzes loan portfolio risk, predicts borrower defaults, generates business insights, and enables conversational analytics using PandasAI and LangChain.

---

## Project Overview

Financial institutions rely on accurate risk assessment to reduce loan defaults and maintain a healthy lending portfolio. This project simulates a real-world banking analytics engagement by combining:

- Data Quality Auditing
- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- Machine Learning Risk Prediction
- Threshold Optimization
- Automated Reporting
- Generative AI Analytics with PandasAI
- Natural Language Querying using LangChain

The final solution helps banking stakeholders identify high-risk borrowers, understand default drivers, and improve lending decisions.

---

## Problem Statement

FinTrust Bank, a mid-size retail bank operating across 20 U.S. states, has experienced a portfolio default rate of approximately **38%**, significantly higher than the industry benchmark of **20–25%**.

The objective of this project is to:

- Identify key factors driving loan defaults.
- Develop a predictive model to estimate borrower risk.
- Improve loan approval decision-making.
- Create an analytics framework for ongoing portfolio monitoring.
- Enable business users to query data using natural language.

---

## Dataset Information

The dataset contains **1,200 loan applications** and **21 features**.

### Features

| Column | Description |
|----------|-------------|
| application_id | Unique Loan Application ID |
| application_date | Loan Application Date |
| branch_id | Branch Identifier |
| state | Applicant State |
| applicant_age | Applicant Age |
| annual_income | Annual Income |
| employment_type | Employment Category |
| employment_years | Years of Employment |
| credit_score | Credit Score |
| existing_debt_balance | Existing Outstanding Debt |
| num_credit_lines | Number of Credit Lines |
| num_prev_loans | Previous Loans Taken |
| prev_defaults | Previous Default Count |
| loan_amount | Requested Loan Amount |
| loan_purpose | Purpose of Loan |
| loan_term_months | Loan Tenure |
| interest_rate | Interest Rate |
| monthly_payment | Monthly EMI |
| debt_to_income | Debt-to-Income Ratio |
| risk_grade | Bank Assigned Risk Category |
| loan_default | Target Variable (Default / Non-Default) |

---

## Project Workflow

### Task 1: Data Quality Audit

Performed comprehensive quality checks including:

- Missing Value Analysis
- Duplicate Detection
- Invalid Data Checks
- Outlier Identification
- Data Profiling Report

---

### Task 2: Data Cleaning Pipeline

Implemented reusable data cleaning functions:

- Missing value treatment
- Duplicate removal
- Data type corrections
- Outlier handling
- Feature engineering

Generated a cleaned dataset for downstream analytics.

---

### Task 3: Exploratory Data Analysis

Business-focused analyses performed:

- Default Rate by Loan Purpose
- Default Rate by Risk Grade
- Credit Score Distribution
- Correlation Analysis
- Monthly Application Trends
- Employment Type Risk Analysis
- Interest Rate vs Risk Analysis
- Branch Performance Comparison
- Debt-to-Income Band Analysis

---

### Task 4: Machine Learning Risk Prediction

Built predictive models to classify loan defaults.

#### Models Evaluated

- Logistic Regression
- Random Forest Classifier

#### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

### Task 5: Threshold Optimization

Optimized probability thresholds to improve business outcomes.

Benefits:

- Better identification of risky borrowers
- Improved Recall for defaults
- Reduced portfolio risk exposure

---

### Task 6: Automated Analytics Reporting

Generated a structured Excel-based analytics report containing:

- Executive Summary
- Data Quality Findings
- Cleaning Summary
- EDA Insights
- Branch Performance Analysis
- Model Evaluation Results
- Threshold Optimization Results

---

### Task 7: Conversational Analytics with AI

Implemented AI-powered analytics using:

#### PandasAI

Users can ask questions such as:

```python
Which employment type has the highest default rate?
```

```python
Identify the top 5 factors associated with loan default.
```

```python
Which DTI band has the highest default rate?
```

---

#### LangChain Data Agent

Built a conversational analytics assistant capable of:

- Natural Language Querying
- Multi-turn Analysis
- Data Exploration
- Automated Insight Generation

Example:

```text
Which employment type has the highest default rate?
```

Follow-up:

```text
What is the average loan amount for those borrowers?
```

---

## Key Business Insights

Some notable findings from the analysis include:

- Higher risk grades exhibited significantly higher default rates.
- Borrowers with lower credit scores were more likely to default.
- Debt-to-Income ratio emerged as an important risk indicator.
- Certain employment categories displayed elevated risk levels.
- Previous defaults strongly correlated with future default behavior.

---

## Technologies Used

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn

### Reporting

- OpenPyXL

### Generative AI

- PandasAI
- LiteLLM
- Google Gemini

### LLM Orchestration

- LangChain
- LangChain Experimental Agents

---

## Project Structure

```text
├── bank_loan_data.csv
├── AI Loan Analytics.ipynb
├── Loan_Portfolio_Analytics_Report.xlsx
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/loan-portfolio-risk-analytics.git

cd loan-portfolio-risk-analytics
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
AI Loan Analytics.ipynb
```
Enter your Google Gemini API Key for running Pandas AI and Langchain Agents without which the agentic code will fail.
Run all cells sequentially.

---

## Future Enhancements

- XGBoost Implementation
- Model Explainability with SHAP
- Streamlit Dashboard
- Real-Time Risk Scoring API
- Azure Deployment
- Power BI Integration
- Automated Model Monitoring

---

## Learning Outcomes

This project demonstrates practical experience in:

- Data Cleaning
- Exploratory Data Analysis
- Risk Analytics
- Machine Learning Classification
- Model Evaluation
- Threshold Optimization
- Report Automation
- Generative AI Integration
- LangChain Applications
- Conversational Business Intelligence

---

## Author

**Nikhil Deshpande**

Data Analyst | Power BI Developer

Skills:
- SQL
- Power BI
- Python
- Pandas
- Machine Learning
- Data Visualization
- Generative AI Analytics

---
