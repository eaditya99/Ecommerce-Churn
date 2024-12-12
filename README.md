# eCommerce Churn Analysis

## Background
Customer churn is a significant challenge for eCommerce businesses, impacting revenue and growth. Understanding the factors that contribute to churn can help businesses improve customer retention strategies and enhance overall service quality.

## Problem Statement
The project addresses several key challenges faced by eCommerce businesses:

- **Predicting Customer Churn**: Identifying customers who are likely to churn allows businesses to take proactive measures to retain them.
- **Understanding Churn Drivers**: Analyzing customer behavior and transaction data to understand the factors influencing churn.
- **Improving Customer Retention**: Developing strategies to improve customer satisfaction and loyalty.
- **Enhancing Revenue**: Identifying opportunities to increase customer lifetime value.

## Objective
The objective of this project is to leverage machine learning techniques to:

1. **Predict Churn**: Build models to accurately predict customer churn.
2. **Analyze Customer Behavior**: Understand patterns and behaviors that lead to churn.
3. **Identify Key Churn Drivers**: Determine the most significant factors contributing to customer churn.
4. **Provide Actionable Insights**: Offer recommendations to improve customer retention and increase revenue.

## Description of Features

| Features                      | Description                                                                                                       |
|-------------------------------|-------------------------------------------------------------------------------------------------------------------|
| `CustomerID`                  | Unique customer ID                                                                                                |
| `Churn`                       | Churn Flag (1 for churned, 0 for retained)                                                                        |
| `Tenure`                      | Tenure of the customer with the organization                                                                      |
| `PreferredLoginDevice`        | Preferred login device of the customer                                                                            |
| `CityTier`                    | City tier indicating the customer's location type                                                                 |
| `WarehouseToHome`             | Distance between the warehouse and the customer's home                                                            |
| `PreferredPaymentMode`        | Preferred payment method of the customer                                                                          |
| `Gender`                      | Gender of the customer                                                                                            |
| `HourSpendOnApp`              | Number of hours spent on the mobile application or website                                                        |
| `NumberOfDeviceRegistered`    | Total number of devices registered by the customer                                                                |
| `PreferedOrderCat`            | Preferred order category of the customer in the last month                                                        |
| `SatisfactionScore`           | Customer satisfaction score                                                                                       |
| `MaritalStatus`               | Marital status of the customer                                                                                    |
| `NumberOfAddress`             | Total number of addresses added by the customer                                                                   |
| `Complain`                    | Indicates if any complaint was raised in the last month                                                           |
| `OrderAmountHikeFromlastYear` | Percentage increase in order amount from the previous year                                                        |
| `CouponUsed`                  | Total number of coupons used in the last month                                                                    |
| `OrderCount`                  | Total number of orders placed in the last month                                                                   |
| `DaySinceLastOrder`           | Number of days since the last order placed by the customer                                                        |
| `CashbackAmount`              | Average cashback received in the last month                                                                       |

## Technologies

- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - XGBoost
- **Tools**: Jupyter Notebook
