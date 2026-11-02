# Telco-Customer-Churn

### Table of content
- [Project overview](#Project-overview)
- [Data sources](#Data-sources)
- [Tools](#Tools)
- [Data cleaning](#Data-cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Insights](#Insights) 
- [Recommendations](#Recommendations)

## Project overview
This dataset contains customer-level records from a telecommunications company. It tracks a fictional telecommunications company's customer profiles to analyze retention and predict churn. Each row represents a single customer with service usage, contract details, billing information, and a binary churn label. The data is structured to track operational, financial, and behavioral health metrics. 

## Data sources
- Project Jupyter notebook
  
## Tools
- excel
- python
- pandas
- matplotlib
- plotly express
- Numpy
- seaborn

## Data cleaning
1. Cleaning columns
2. Count missing value in each column
3. Removing duplicate
4. Change data type of "monthly_charges from object to float
5. Outlier detection

## Exploratory Data Analysis
### a. Customer Retention & Churn Dynamics
1. What percentage of customers that left the company within the last month?
2. How do demographics impact a subscriber's tendency to switch providers?
3. Do new customers churn at a higher rate than long-term subscribers?
4. How much higher is the churn velocity for customers on Month-to-month contracts compared to One-year or Two-year agreements?
5. Compared to Two-year agreements: Month-to-month churn.
6. Compared to One-year agreements with Month-to-month contract.

### b. Services & Product Performance
1. Do subscribers who sign up for add-ons like Online Security, Tech Support, or Online Backup stay longer?
2. Is there a high churn rate among customers who only have Fiber Optic internet versus DSL?
3. Do customers using Streaming TV or Streaming Movies demonstrate higher brand loyalty? 

### c. Financial Impact & Contract Optimization
1. What is the total revenue lost from monthly charges due to departing customers?
2. Are customers using paperless billing or electronic checks more prone to leaving than those on automatic credit card payments?
3. How significantly does a one-year or two-year contract reduce churn compared to a month-to-month plan?
   
## Insights
1. Overall churn rate: 26.54% (1,869 churned customers)
2. Customers in their first 19th months have the highest churn rate: 41.09%
3. Month-to-Month contracts have the highest churn rate at approximately 28.0%
4. Fiber Optic customers have the highest churn rate at approximately 27.78%
5. Mailed Check customers have a lower churn rate than customers using Credit Card, Bank transfer or electric check

| **Total Customers:** 7043 |
| --- |
| **Churned Customers:** 1869 |
| **Baseline Churn Rate:** 26.54% |


<img width="938" height="500" alt="%last_month" src="https://github.com/user-attachments/assets/4003c2e3-2847-4184-8213-e7d39f6e83c5" />


Churn Rate by Demographics 

| churn | senior_citizen | dependents |Churn Rate (%) |
| :--- | :---: | :---: | ---: |
|0  |  0    |  No     |  29.60 |
|1  |  0    |  Yes    |  16.05 |
|2  | 1     |  No     |  32.64 |
|3  | 1     |  Yes    |  19.78 |




<img width="900" height="800" alt="sub_1" src="https://github.com/user-attachments/assets/66542262-45ef-49fc-b82b-d987f1e574fd" />


### Services & Product Performance

<img width="1000" height="800" alt="sub_2" src="https://github.com/user-attachments/assets/526f048d-7fed-4611-8474-5f8a5a74f283" />


### Financial Impact & Contract Optimization
<img width="900" height="900" alt="sub_3" src="https://github.com/user-attachments/assets/0f70f9e5-19e6-4f22-8a95-989993c513df" />


## Recommendations
1. Improve onboarding and retention activity during the first six months.
2. Encourage eligible Month-to-Month customers to move to longer contracts.
3. Investigate Fiber Optic pricing, service quality, and support experience.
4. Strengthen device offers, data plans, and competitor-focused retention campaigns.
5. Improve customer-support interactions through service training.
