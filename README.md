# Telecom-Company-Customer-Churn
The goal of the Project is to understand the factors impact the churning of customers in telecom companies and to build a model that predicts the same.

## About the dataset

The dataset is of telecom company and includes customer information and whether a particular customer has churned or not. It includes three kinds of information about the customer.

Demographic Information: Age, Gender, Partner, Dependents

Customer Account Information: Tenure, Contract, Payment Method, Paperless Billing, Monthly Charge and Total Charge

Services Used: Phone, Multiple Lines, Internet, Online Security, Online Backup, Device Protection, Tech Support, and Streaming TV and Movies

The dataset has information about 7043 customers and 21 features.

## Results obtained from Exploratory Data Analysis:

1.Since the customers who do not use internet service provide very little revenue to the company, they were excluded from the analysis.

2.Out of a total of 5512 customers 1756 which is 31.85% have churned.

3.We found out gender does not play a role in predicting whether a customer will churn or not because more or less equal number of customers have churned of each gender.

4.Customers who have a longer tenure with the company churned less compared to customers with lesser tenure. Similar resutls were found with the length of contracts.

5.Customers who spend less are more likely to churn compared to customers who spend more. This can be attributed to the spending ability of the customer and how many products     the customer is using.

6.Customers who use electronic checks and paperless billing churn more compared to others.

7.We found out that more support the user subscribes to of the telecom company the more likely he is to stick to the telecomm company.

8.Customers who are independent are more likely to churn. This can be attributed to the financial stability of the customer.

9.Online Backup and Device Protection turned out to be the most frequently bought support sytems by the customers.

10.There is not much significant difference in total charges between customers who only watched tv versus customers who only watched movies.

11.More revenue is obtained from partners compared to single customers.

## Models applied and their accuracies

Logistic Regression: 77%

K Nearest Neighbors: 75%

Support Vector Machines: 77%

Decision Trees: 69%

Random Forest: 78%

### The Random Forest was the best predictor of the customer churn with an accuracy of 78% on the test set
