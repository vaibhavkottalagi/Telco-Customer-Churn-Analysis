# Telco-Customer-Churn-Analysis
This analysis investigates customer attrition patterns within a telecommunications provider using the Telco Customer Churn dataset from Kaggle. By modeling transactional and demographic metrics across 7,000 customers, the dashboard highlights primary drivers of churn—specifically contract type, customer tenure, service feature adoption.
Detailed Dashboard Breakdown

High-Level KPIs:

Total Customers: 7,000 (7K) total records analyzed.

Churn Rate: 26.54%, representing 2,000 total churned customers.

Risk Segmentation: Among retained customers, 4,541 are classified as Normal Risk, while 633 fall into the High-Risk category.

Contract & Tenure Dynamics:

Contract Distribution: Month-to-month contracts account for the overwhelming majority of lost customers (1,655 churned), compared to long-term commitments (166 for 1-Year, 48 for 2-Year contracts).

Tenure Vulnerability: Customer loss is heavily front-loaded. Accounts in the 0–6 Months tenure band show a 52.94% churn rate, dropping to 35.89% for 6–12 months, and stabilizing at 17.13% for 12+ months.

Services & Monthly Charges Impact:

Add-On Security Services: Lack of core support features correlates with higher monthly charge volume among churners—customers without OnlineSecurity ($157K total monthly charges) or OnlineBackup ($107K total monthly charges) show elevated churn volume compared to those enrolled in these services.

Revenue & Pricing: Retained and churned accounts both average around $74/month in high-tier segments, indicating that price sensitivity combined with short contract commitments triggers early drop-off.

Actionable Business Recommendations

Onboarding Incentives: Target customers in their first 6 months with engagement offers to bridge the high-risk 52.94% churn window.

Contract Migration: Offer discounted rates or bundled add-ons to transition Month-to-Month users into 1-Year or 2-Year plans.

Service Bundling: Automatically attach Online Security and Online Backup trials to new subscriptions to boost retention.
