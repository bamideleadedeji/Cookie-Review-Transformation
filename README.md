# Cookie-Review-Transformation
The modeling objective is to build and test a deccision tree model that uses banking data to predict whether a customer will churn. If a customer churn, it means they left and took their business elsewhere. If we can predict customers who are likely to churn, we can take measures to retain, them before the do.
These measures could be promotions, discounts or other incentives to boost customers satisfactions and therefore retention.
# Features
Identification Features (Often dropped in modeling)

RowNumber: Unique row identifier.
CustomerId: Unique identifier for each customer.
Surname: Customer's last name.
# Demographic Features

Geography: The country where the customer resides (e.g., France, Spain, Germany).
Gender: The customer's gender (Male or Female).
Age: The customer's age
Financial and Relationship Features

# CreditScore: A numerical value representing the customer's credit score.
Tenure: The number of years the customer has been with the bank.
Balance: The customer's account balance.
EstimatedSalary: The estimated salary of the customer.
NumOfProducts: The number of bank products the customer is using.
HasCrCard: Whether the customer has a credit card (Binary: 1 = Yes, 0 = No).
IsActiveMember: Whether the customer is an active member (Binary: 1 = Yes, 0 = No).

# Target Variable

Exited: Whether the customer has churned (left the bank) or not (Binary: 1 = Yes, 0 = No).
