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
Recall measures the ratio between the number of employee that are predicted to attrite who actually left the  company, and the number of employee that are predicted to stay but actually left the company. Maximizing recall means minimizing the number of employee who are incorrectly predicted to not attrite.
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/ME%202.png)

## Feature Importance
The most influential features in the model are MaritalStatus_Married, Age, and TotalWorkingYears.
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/FI%201.png)

## Recommendation
**1. Recomendation  for MaritalStatus** <br>
   - Develop employee benefits programs by offering additional benefits such as family health insurance, additional leave for family events, or educational support for employees' spouses or children.
   - Develop a family support program that includes family counseling, financial planning assistance, or work time flexibility to help employees balance their work and personal lives.<br>
   
**2. Recomendation  for Age** <br>
   - Develop generation-specific training programs, cross-generational mentoring, or flexible online learning opportunities.
   - Develop mental health counseling, physical fitness programs, or health seminars for age-relevant issues.
   - Offer additional retirement savings options or health insurance with additional coverage for employees approaching retirement. <br>
   
**3. Recomendation  for TotalWorkingYears**
   - Develop additional training, skill development courses, or mentoring programs to help employees improve their competencies and advance their careers.
   - Design internal knowledge management programs or collaboration forums to facilitate the exchange of knowledge and experience between employees.
   - Develop special retention programs that offer incentives or additional benefits to experienced employees to retain them in the long term. <br>

## Business Impact
Before the model, the attrition rate was 16.1%, and it decreased by 7.7% after the model, resulting in an attrition rate of 8.4%.
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/BI%201.png)
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/BI%202.png)

## Summary
![alt Text](https://github.com/shaniawp/Bank-Customer-Churn-Prediction/blob/main/SUM.png)
