# Telco-Customer-Churn
## Project overview
This dataset contains customer-level records from a telecommunications company. It tracks a fictional telecommunications company's customer profiles to analyze retention and predict churn. Each row represents a single customer with service usage, contract details, billing information, and a binary churn label. The data is structured to track operational, financial, and behavioral health metrics. 
## Data sources
## Tools

## Data cleaning
1. Cleaning columns
2. Count missing value in each column
3. Removing duplicate
4. Change data type of "monthly_charges from object to float
5. Outlier detection

## Exploratory Data Analysis
### a. Customer Retention & Churn Dynamics
1. What percentage of customers that left the company within the last month?
2. How do demographics  (senior_citizens and dependents) impact a subscriber's tendency to switch providers?
3. Do new customers churn at a higher rate than long-term subscribers?
4. How much higher is the churn velocity for customers on Month-to-month contracts compared to One-year or Two-year agreements?
5. Compared to Two-year agreements: Month-to-month churn is roughly 15.2 to 16.9 times higher (a difference of about 39.9 to 44.6 percentage points).
6. Compared to One-year agreements with Month-to-month contract

### b. Services & Product Performance
1. Do subscribers who sign up for add-ons like Online Security, Tech Support, or Online Backup stay longer?
2. Is there a high churn rate among customers who only have Fiber Optic internet versus DSL?
3. Do customers using Streaming TV or Streaming Movies demonstrate higher brand loyalty?
4. 

### c. Financial Impact & Contract Optimization
1. What is the total revenue lost from monthly charges due to departing customers?
2. Are customers using paperless billing or electronic checks more prone to leaving than those on automatic credit card payments?
3. How significantly does a one-year or two-year contract reduce churn compared to a month-to-month plan?
   
## Insights
### Problem statement
This telecommunications company faces a signi cant customer retention challenge with 1,869 customers churning out of 7,043 total customers , representing a 26.54% churn rate . The  nancial impact is substantial, with $2,862,927 in revenue loss from churned customers, representing 17.8% of the company's total revenue base of $16.1 million.
###  key business challenges
The IBM Telco Customer Churn Dataset highlights a 26.5% overall customer churn rate, revealing several core business and operational challenges for telecommunications providers:
1. High Churn in Short-Term Tenures: Attrition heavily concentrates in the first 1 to 6 months of a customer's lifecycle (52.1% churn rate for those with 0–12 months of tenure), indicating a weak onboarding and early-engagement experience.
2. Vulnerability of Month-to-Month Contracts: Customers on month-to-month agreements churn at a rate of 47.4%, compared to just 2.8% for two-year contract holders, exposing the company to high revenue volatility. 
3. Lack of Value-Added Services (VAS): Customers missing critical support features—such as online security and tech support—churn at nearly double the rate (~41%) of those who subscribe to them, highlighting missed cross-selling and customer-support opportunities. 
4. Friction with Payment Methods: Users paying via electronic check experience a 45.3% churn rate, significantly higher than customers enrolled in automated payment methods (15–16%). 
5. Price Sensitivity vs. Fiber Optic Dissatisfaction: Fiber optic internet subscribers show a high churn rate of 41.9% (compared to 19.6% for DSL), often linked to high monthly bills (80–120 tier showing a 37.9% churn rate) that fail to deliver perceived value or reliability. 
6. Data Quality & Pipeline Issues: Raw operational records often feature missing values in billing fields (such as string formatting errors in TotalCharges for new accounts) and severe target-class imbalance, complicating data engineering and predictive modeling efforts. 



## Recommendations

