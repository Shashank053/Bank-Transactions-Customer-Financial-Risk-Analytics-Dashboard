# Bank Transactions & Customer Financial Risk Analytics Dashboard

End-to-end analytics project that scores ~150,000 bank customers for credit/delinquency
risk and surfaces the results in an interactive Power BI dashboard.

## Pipeline
Kaggle dataset → Python/scikit-learn (cleaning, feature engineering, logistic regression
risk scoring) → Azure SQL Database → Power BI dashboard

## Tools
Python (pandas, scikit-learn, SQLAlchemy) · Azure SQL Database · Power BI Desktop

## Key Results
- Logistic regression model, AUC ≈ 0.83 on held-out test data
- Segmented ~150,000 customers into Low/Medium/High risk tiers
- Dashboard highlights that [insert one real insight, e.g. "customers in the
  'Very High' debt-ratio bucket make up the largest share of the High Risk tier"]

## Files
- `Bank_risk_project_.ipynb` — full notebook: data cleaning, feature engineering, and
  risk-scoring model
- `bank risk analysis project .pbix` — Power BI dashboard file
- `customer_risk_scored.csv` — cleaned, scored output dataset
- `dashboard_overview.png` — dashboard preview (below)

## Dataset
"Give Me Some Credit" — Kaggle: https://www.kaggle.com/datasets/lamine16/give-me-some-credit

## Dashboard Preview
![Bank Transactions Risk Analytics](bank transactions risk analytics.png)
