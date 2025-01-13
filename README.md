# Customer Churn Analysis <img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png" alt="Python Logo" width="100"/>

## Overview
This project focuses on analyzing customer churn using a dataset that includes various customer attributes and behavioral metrics. The goal is to understand the factors contributing to customer churn and develop predictive models to forecast churn.

## Dataset Description
The dataset contains 440,833 entries with the following columns:

- **CustomerID**: unique identifier for each customer
- **Age**: age of the customer
- **Gender**: gender of the customer (Male, Female)
- **Tenure**: duration of customer relationship in months
- **Usage Frequency**: average usage frequency of the service
- **Support Calls**: number of support calls made by the customer
- **Payment Delay**: average delay in payment (in days)
- **Subscription Type**: type of subscription the customer has (Standard, Premium, Basic)
- **Contract Length**: length of the customer’s contract (Annual, Quarterly, Monthly)
- **Total Spend**: total amount spent by the customer
- **Last Interaction**: time since the last interaction with the customer (in days)
- **Churn**: whether the customer has churned (1: churned, 0: not churned)

## Project Workflow

1. **Data Preprocessing**:
   - Handled missing values and encoded categorical data.
   - Scaled features for better model performance.

2. **Model Implementation**:
   - **Linear Regression**: Identified linear relationships between features and churn.
   - **K-Nearest Neighbors (KNN)**: Classified customers into churned or non-churned categories.

3. **Model Evaluation**:
   - Evaluated using metrics such as accuracy, precision, and recall.

## Conclusion
The project provided insights into customer churn and built models to predict churn, helping businesses improve customer retention strategies.

---

📂 This project was developed using Python with libraries like Pandas, NumPy, and Sklearn.

