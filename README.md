# Credit Card Default Risk Analysis

A statistical analysis project focused on understanding factors associated with credit card default risk using Python, Exploratory Data Analysis (EDA), feature engineering, and hypothesis testing.

## 📌 Project Overview

Credit card defaults create financial risks for lending institutions. Understanding customer repayment behaviour and identifying financial patterns associated with defaults can help businesses make better credit risk management decisions.

This project analyses historical credit card customer data to investigate whether factors such as credit utilization, payment amounts, and credit limits differ between customers who defaulted and those who did not.

## 🎯 Business Objectives

- Understand customer default patterns through exploratory data analysis.
- Examine the relationship between repayment behaviour and default status.
- Analyse differences in credit utilization, average payment amounts, and credit limits.
- Apply statistical hypothesis testing to determine whether observed group differences are statistically significant.
- Translate statistical findings into practical business recommendations.

## 📊 Dataset

- **Dataset:** Default of Credit Card Clients
- **Source:** UCI Machine Learning Repository
- **Geography:** Taiwan
- **Data Period:** Historical dataset (2005)
- **Final Records:** 29,965
- **Target Variable:** `default payment next month`

The target variable indicates whether a customer defaulted on their next month's payment.

## 🛠️ Tools & Technologies

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- SciPy
- Jupyter Notebook

## 🔍 Project Workflow

1. Data loading and preprocessing
2. Data quality checks and duplicate removal
3. Exploratory Data Analysis (EDA)
4. Customer default distribution analysis
5. Repayment status and credit behaviour analysis
6. Feature engineering:
   - Average Bill Amount
   - Credit Utilization
   - Average Payment Amount
7. Statistical hypothesis testing using Welch's Independent Samples t-test
8. Interpretation of results and business recommendations

## 📈 Key Findings

- Approximately **22.13%** of customers in the dataset defaulted on their next payment.
- Customers who defaulted had higher average credit utilization (44.97%) compared with non-defaulting customers (35.18%).
- Average payment amounts were lower among defaulting customers (3,331.23) than non-defaulting customers (5,835.36).
- The average credit limit was lower for defaulting customers (129,984.57) compared with non-defaulting customers (178,084.51).
- All three comparisons showed statistically significant differences at the 5% significance level.

## 🧪 Statistical Analysis

Three independent hypothesis tests were conducted using Welch's t-test:

| Variable | Default Group Mean | Non-Default Group Mean |
|---|---:|---:|
| Credit Utilization | 44.97% | 35.18% |
| Average Payment Amount | 3,331.23 | 5,835.36 |
| Credit Limit | 129,984.57 | 178,084.51 |

**Significance Level (α):** 0.05

The results indicate statistically significant differences between defaulting and non-defaulting customers across all three variables.

## 💡 Business Recommendations

- Monitor customers with consistently high credit utilization.
- Pay attention to customers making relatively low payments against their outstanding balances.
- Consider repayment behaviour alongside credit limits when reviewing customer risk.
- Use customer repayment patterns to support credit risk monitoring strategies.

## 📁 Repository Structure

```text
Credit-card-default-risk-analysis/
│
├── Credit_Card_Default_Risk_Analysis (1).ipynb
├── Credit_Card_Default_Risk_Analysis_BRD.pdf
├── README.md
└── .gitignore
```

## 📄 Project Documentation

The Business Requirements Document (BRD) is included in this repository and outlines the business problem, objectives, analytical scope, methodology, and recommendations.

## ⚠️ Limitations

- The analysis uses historical data from Taiwan (2005), not current credit card customer data.
- Statistical significance does not establish causation.
- The project focuses on statistical analysis and does not build a machine learning prediction model.
- Findings should not be directly generalized to today's credit card market without further validation.

## 👤 Author

**Aman Khan**

