# Customer Churn Analysis

**The business problem:**
We’re a telco startup. Our churn rate is high, and leadership needs to know: Who’s churning, why, and how can we stop it?

## Objective:
Segment the customer base and analyze **behavioral** & demographic patterns causing the churn, using SQL, Excel, and Tableau.
## Tools used:
SQL (MySQL) → Data wrangling, cohort segmentation, churn metrics.
Excel → Quick summaries, pivot tables.
Tableau → Data storytelling via dashboards.

# Key Findings
## Contract Type Performance Analysis
<img width="1411" height="776" alt="image" src="https://github.com/user-attachments/assets/7c2907fc-8149-407d-af9f-57302fcfe0dd" />

Month-to-month contracts show higher churn rates (~45%) compared to longer-term contracts:
1. Month-to-month: 45% churn rate.
2. One-year contracts: ~11% churn rate
3. Two-year contracts: ~3% churn rate

## Early Tenure Vulnerability Pattern
<img width="1357" height="765" alt="image" src="https://github.com/user-attachments/assets/ef8a53c9-9caa-481f-bf2c-d31801690255" />

Customers face elevated churn risk in months 1-6:
1.Month 1: 65% churn rate (highest risk period).
2.Months 2-6: 40-60% churn rates with high volatility
3.Stabilization occurs around month 24+ (sub-10% churn rates)


## Long-term Customer Value 
<img width="838" height="251" alt="image" src="https://github.com/user-attachments/assets/31f8ac38-e057-40b5-891b-b515082fa8bc" />

Tenure-Revenue Relationship:
1.Customers with 24+ month tenure show minimal churn (<10%)
2.Revenue stability increases significantly after the 12-month mark


## Revenue vs. Retention Dynamics
<img width="1571" height="782" alt="image" src="https://github.com/user-attachments/assets/7a220b29-86fe-4be9-afb0-f33562da1062" />

Pricing Strategy Implications:
1.Higher monthly charges ($60-100) correlate with increased churn likelihood.
2.Sweet spot appears to be $40-60 monthly charges for optimal retention
3.Customers paying $0-20 show mixed retention (likely promotional/trial customers)



