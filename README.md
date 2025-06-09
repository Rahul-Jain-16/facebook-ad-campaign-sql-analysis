# 📊 Facebook Ad Campaign Effectiveness Analysis

A business-focused SQL project to uncover ROI patterns, audience performance, and ad fatigue in Facebook ad campaigns.

## Summary
This project answers key business questions using SQL and Python visualization:

- 🧠 Which campaigns are giving the best return on ad spend (ROAS)?
- 👥 Which audience segments (by age) perform best?
- 📉 Are there signs of ad fatigue over time?
- 💸 Are we overspending on low-performing campaigns?

The analysis is based on anonymized ad performance data from a Facebook marketing dataset provided by Kaggle.

## 🔍 Key Findings

- **Campaign 1178** spent more than $16k but returned the lowest efficiency (0.06 conversions per dollar). 
- **Campaign 916**, despite tiny spend, delivered the **highest ROI** (0.38 conversions per $).
- Strong **evidence of ad fatigue** in Campaign 1178 — CTR dropped and stayed low over time.

<img src="Images/CTR and CVR by age group.png" width="600">
<img src="Images/CTR trends.png" width="600">

## 🧪 Code & Notebook

All SQL queries and charts are in [`facebook_ads_SQL_project.ipynb`](facebook_ads_SQL_project.ipynb).

To run it:

1. Open in Google Colab or Jupyter
2. Install dependencies (SQLite, pandas, matplotlib)
3. Run SQL queries on the embedded database

## 🛠️ Skills Demonstrated

- SQL analytics and business metrics
- Click-through and conversion analysis
- Ad performance reporting
- Data cleaning and preparation
- Visual storytelling with Matplotlib

