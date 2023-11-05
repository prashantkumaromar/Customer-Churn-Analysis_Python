# Customer Churn Analysis in Banking Sector

## Group 58

### Introduction

Customer churn is a critical issue in the banking sector, referring to the loss of clients or customers. Retaining an existing customer base is crucial, as acquiring new customers is significantly more expensive. The banking industry faces a high churn rate due to customers seeking safe options, high returns, low-interest rates, and various benefits.

### Motivation

Understanding customer churn is vital for banks to:
- Enhance their functionality and attract more customers.
- Reduce costs associated with acquiring new customers.
- Increase profitability and referrals from long-term customers.
- Mitigate the profit loss associated with customer churn.
- Address the increased churn rates during economic downturns.

### Project Scope

This project involves:
1. **Data Import into SQLite**: Organizing raw data into structured format and importing into SQLite.
2. **Exploratory Data Analysis (EDA)**: Identifying factors responsible for churn through data visualization.
3. **Predictive Modeling**: Developing models to predict churn based on these factors.

### Data Definition

- **General Information**: Includes CustomerID, CreditScore, Tenure, and EstimatedSalary.
- **Personal Information**: Contains personal details of customers.
- **Bank Information**: Bank-related data.
- **Status Information**: Activity and exit status of customers.

### Exploratory Data Analysis

The analysis includes:
- Pie charts representing customer exit percentage.
- Bar graphs showing IsActiveMember status, Gender, and Country vs Churn rate.
- Correlation matrix to understand variable relationships.

### Analysis and Predictive Modeling

Two predictive models were compared:
1. **Logistic Regression**: Suitable for binary dependent variables.
2. **Random Forest**: An ensemble learning method using multiple decision trees.

### Results

- Logistic Regression Accuracy: 78.9%
- Random Forest Accuracy: 86.4%

### Conclusion

Random Forest proved more accurate, especially effective with categorical variables and non-linearity. These models can help banks understand factors influencing customer churn and improve services to attract and retain customers.

### Resources

- Dataset: [Kaggle Dataset](https://www.kaggle.com/code/kmalit/bank-customer-churn-prediction/data)
- Code Link: [Project Code](https://buffalo.box.com/s/9ixs1cfhzzybnzrq338plvf0ddl1vwh1)

