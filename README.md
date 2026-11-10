# Customer Churn Prediction

Predicting which telecom customers are likely to leave the company, using Python and machine learning.

## Dataset
Telco Customer Churn dataset (7,043 customers, 21 columns).

## Steps
1. Data cleaning (fixed TotalCharges, removed 11 empty rows)
2. Exploratory data analysis (EDA)
3. One-hot encoding of text columns
4. Train/test split (80/20)
5. Models: Logistic Regression, Random Forest

## Key Insights
- Month-to-month contract customers churn the most.
- New customers (low tenure) churn more than long-term customers.
- About 26% of customers churned, so the data is imbalanced.

## Results
Logistic Regression: accuracy 0.79, churn recall 0.52.

## Tools
Python, pandas, seaborn, matplotlib, scikit-learn
