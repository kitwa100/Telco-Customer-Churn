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
The primary business challenge highlighted by the Telco customer churn dataset is high customer churn (around 26.5% of the subscriber base leaving), which directly drains recurring monthly revenue.
- Key business and operational drivers behind this challenge, as revealed through the dataset, include:

1. Contract Commitment Structure

• Month-to-Month Contracts: Customers on month-to-month plans exhibit significantly higher churn rates than those locked into one-year or two-year contracts.
• Lack of Long-Term Lock-in: The absence of binding agreements makes it easy for subscribers to switch providers at the first sign of friction or better competitor pricing.

2. Early-Tenure Attrition

• First 1–6 Months: Churn peaks heavily during the initial months of the customer lifecycle.
• Onboarding Gaps: New subscribers who do not quickly experience value or smooth integration are prone to leaving before covering their initial acquisition costs.

3. Service Bundle Gaps (Value-Add Deficits)

• Missing Support Services: Customers lacking add-ons like Tech Support or Online Security churn at nearly double the rate of protected subscribers.
• Bare-Bones Subscriptions: Subscribers with minimal service packages experience lower "stickiness" or platform integration, making them more vulnerable to leaving.

4. Billing and Payment Friction

• Paperless Billing & Payment Methods: Specific billing configurations and electronic payment types correlate with elevated drop-off rates.
• Perceived Cost vs. Value: Higher monthly charges paired with perceived internal service deficiencies accelerate customer departure.

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
