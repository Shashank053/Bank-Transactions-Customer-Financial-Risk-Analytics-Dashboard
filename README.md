# Bank Transactions & Customer Financial Risk Analytics Dashboard

End-to-end analytics project that scores ~150,000 bank customers for credit/delinquency
risk and surfaces the results in an interactive Power BI dashboard.

## Pipeline
Kaggle dataset → Python/scikit-learn (cleaning, feature
engineering, logistic regression risk scoring) → Azure Blob Storage + Azure SQL Database
→ Power BI dashboard

## Tools
Python (pandas, scikit-learn, SQLAlchemy)  · Azure Blob Storage ·
Azure SQL Database · Power BI Desktop

## Key Results
- Logistic regression model, AUC ≈ 0.8X on held-out test data
- Segmented customers into Low/Medium/High risk tiers
- Dashboard highlights that [insert the one real insight you found, e.g.
  "customers with 2+ past-due incidents account for X% of high-risk tier"]

## Repo Structure
- `/notebooks` — Python cleaning, feature engineering, and risk-scoring notebook
- `/powerbi` — Power BI .pbix dashboard file
- `/screenshots` — dashboard preview images

## Dataset
"Give Me Some Credit" — Kaggle: https://www.kaggle.com/datasets/lamine16/give-me-some-credit
(raw file not included in repo per Kaggle's terms; download from the link above)

## Dashboard Preview
![Dashboard overview] bank transactions risk analytics.png
![Risk by age and debt ratio](screenshots/risk_segments.png)
