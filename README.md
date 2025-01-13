# Bank Customer Churn Prediction Dataset

## About Dataset

This dataset contains customer information from a bank to predict customer churn. The data includes various customer attributes and behaviors that can be used to predict whether a customer will leave the bank (churn) or not.

## Dataset Description

- Total columns: 12
- Predictor columns: 11
- Target column: `churn` (1 = customer left the bank, 0 = customer stayed)

## Detailed Column Description

| Variable | Description | Type | Details |
|----------|-------------|------|---------|
| customer_id | Unique identifier for each customer | Nominal | Unique number assigned to each bank client for clear identification |
| credit_score | Customer's credit score | Numeric | Numerical rating of client creditworthiness (300-850) indicating ability to repay obligations. Higher score means lower risk for the bank |
| country | Customer's country | Categorical | Country of permanent residence (France, Spain, Germany). Enables analysis of geographic differences in client behavior |
| gender | Customer's gender | Binary | Client's gender (Male/Female). Can help identify behavioral differences between genders |
| age | Customer's age in years | Numeric | Client's age at time of data collection. Important factor for understanding age groups and their churn tendencies |
| tenure | Number of years as a bank customer | Numeric | Length of relationship with the bank in years. Indicates customer loyalty and relationship stability |
| balance | Account balance | Numeric | Current balance across all client's accounts in the bank. Expresses client's financial activity |
| products_number | Number of bank products used | Numeric | Number of different products actively used by client (accounts, cards, insurance, loans). Shows level of client engagement |
| credit_card | Whether customer has a credit card | Binary | Indicator (1=Yes, 0=No) of credit card ownership. Important indicator of credit product usage |
| active_member | Whether customer is an active member | Binary | Indicator (1=Yes, 0=No) of client activity. Active client regularly uses banking services |
| estimated_salary | Estimated annual salary | Numeric | Estimated annual income of the client. Key indicator of client's financial situation |
| churn | Whether customer left | Binary | Target variable (1=Yes, 0=No) indicating if client terminated their banking services |

## Purpose

The main purpose of this dataset is to predict customer churn in the banking sector. The dataset enables:

- Identifying high-risk customers with high probability of churning
- Analyzing factors that most influence a client's decision to leave
- Creating predictive models for early identification of potential customer churn
- Supporting decision-making in retention strategies

## Notes

- All monetary values are in the same currency
- Dataset contains no missing values
- Data has been anonymized to protect customer privacy
- Dataset is suitable for binary classification tasks and customer behavior analysis
