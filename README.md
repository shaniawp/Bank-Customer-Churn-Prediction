# About the Client
Technological developments and increasingly fierce competition are pushing companies to not only focus on getting new customers, but also retaining existing customers. Raka Bank is one startup company that focuses on this problem.
Based on the data the company has, Raka Bank wants to identify which aspects encourage customers to churn so that they can provide the right solution to prevent customers from churning.
Raka Bank asked Data Lovelace for help to predict and identify factors that encourage customers to churn.

## The Main Problem
Out of the 10.000 customers, 20.37% or 2.037 customer churn. If the 2.037 customer churn is multiplied by $200 dollars, the cost amounts to $407.400. So, high customer churn causes high  costs.

### **Problem Summary**
- Background : Bank company wants to know which aspects drive the customer to churn and reduce the cost of finding a new banking customer. <br>
- Goals : Decrease churn rate from 20.37% to at least under 15% in order to reduce cost. <br>
- Objectives : Create a model machine learning to predict potential customer churn and identity the factors of customer churn. <br>
- Business Metrics : Churn Rate (%)

## Exploratory Data Analysis
- **Churn Rate by Age** <br>
The majority of customers are Middle age, the lowest are Elderly, and the highest churn rate is Senior.

- **Churn Rate by NumOfProduct** <br>
The majority of customers have 1 NumOfProducts and the lowest is 4. The hight churn rate is customers who have 1 NumOfProduct.

- **Churn Rate by IsActiveMember** <br>
nactive customers are more likely to experience churn than regular customers active.

## Data Preprocessing Flow
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/DP%201.png)

## Modelling
### **Model Comparison**
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/ME%201.png)
Recall measures the ratio between the number of customers that are predicted to leave who actually left the bank company, and the number of customers that are predicted to stay but actually left the bank company. Maximizing recall means minimizing the number of customers who are incorrectly predicted to stay.
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/ME%202.png)

## Feature Importance
The most influential features in the model are Age, NumOfProducts, IsActiveMember.
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/FI%201.png)

## Recommendation
**1. Recomendation  for Age** <br>
   - 33.97% of Senior customers (40 - 50 years old) are predicted to churn, so we recommend : Offer retirement preparation products with high returns. <br>
   
**2. Recomendation  for NumOfProducts** <br>
   - 27,71% of Customers with 1 products predicted to churn, it's higher than customers with 2 products. So, It is necessary to evaluate and treat customers with 1 product by promoting cross selling (i.e offer bundling products). <br>
   
**3. Recomendation  for IsActiveMember**
   - Customer who is not an active member are predicted to churn around 26,85 % . It is around 12 percent higher than churn in active member. 
To increase the activity of inactive member, we recommend to offer low interest and low deposit products to the inactive members. 
The offering to the inactive members can be displayed through several channels such email, sms, social media.. <br>

## Business Impact
Before the model, the churn rate was 20.37%, and it decreased by 8.65% after the model, resulting in an attrition rate of 11.72%.
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/BI%201.png)
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/BI%202.png)

## Summary
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/SUM.png)
