# E-commerce Customer Behaviour Dashboard

## Live Dashboard
[View interactive Tableau dashboard →](https://public.tableau.com/app/profile/rabinarayan.sahu/viz/EcommerceCustomerBehaviourDashboard/Dashboard1?publish=yes)

![Dashboard Preview](images/dashboard_preview.png)

## Project Overview
RFM (Recency, Frequency, Monetary) segmentation analysis of 
541,909 transactions from a UK online retailer (2010–2011).
Customers segmented into Champions, Loyal, At Risk, and Lost 
groups to enable targeted marketing strategies.

## Tools Used
- Python (Pandas, Plotly, SQLite3)
- Tableau Public
- Google Colab
- Dataset: UCI Online Retail Dataset

## Key Findings
1. Champions (top 20% of customers) generate ~60% of total revenue
2. ~28% of customers are "At Risk" — bought frequently but inactive 3+ months
3. UK dominates revenue at 83% — international expansion is a clear opportunity
4. Revenue peaked in November 2011 (holiday season) — inventory should be front-loaded in October
5. Average Champion customer spends 10x more than an At Risk customer

## Skills Demonstrated
- RFM customer segmentation (industry standard method)
- SQL queries using SQLite inside Python (CASE WHEN, window functions)
- Interactive Plotly charts (scatter, bar)
- Tableau Public dashboard with cross-chart filtering
- Business-framed insights with actionable recommendations

## Dashboard Features
- Click any segment bar to filter all charts to that segment
- Scatter plot: each dot = one customer (size = purchase frequency)
- Revenue trend shows seasonal peaks for inventory planning

## Dataset
UCI Machine Learning Repository — Online Retail Dataset
https://archive.ics.uci.edu/ml/datasets/Online+Retail
