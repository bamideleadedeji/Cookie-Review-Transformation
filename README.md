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

Exited: Whether the customer has churned (left the bank) or not (Binary: 1 = Yes, 0 = No).

## Project Motivation & Background
Predicting customer churn helps banks retain customers and improve services. Decision trees are easy to interpret and effective for this type of classification.

## Installation & Requirements
- Python 3.8+
- pandas, scikit-learn, matplotlib  
Install requirements:  
```bash
pip install -r requirements.txt
```

## Usage Instructions
1. Prepare your dataset as described below.
2. Run the main script:  
```bash
python train_model.py
```

## Dataset Details
Data is from a simulated bank customer dataset. Download from [Kaggle](https://www.kaggle.com/datasets).

## Model Performance
The decision tree achieved ~84% accuracy on the test set.

## Contributing
Open to contributions! Please fork the repo, make changes, and submit a pull request.

My Link	Purpose
Badge Image	![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bamideleadedeji/Cookie-Review-Transformation/blob/master/Bank_Churn_customers_(_Turnover_)_.ipynb)

## License
MIT License

## References & Further Reading
- [Introduction to Decision Trees](https://scikit-learn.org/stable/modules/tree.html)
- [Customer Churn Analysis](https://en.wikipedia.org/wiki/Customer_churn)

## Contact Information
Questions? Email bamideleadedeji2000@gmail.com
