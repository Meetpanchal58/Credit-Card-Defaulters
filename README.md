# Credit-Card-Default-Prediction

## Overview
This is a classification model for a most common dataset, Credit Card defaulter prediction. Prediction of the next month credit card defaulter based on demographic and last six months behavioral data of customers.

## Dataset Information
This dataset contains 25 columns and 3000 rows on information of default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in _Taiwan from April 2005 to September 2005_.

| Column Name                       | Description                                                                                                               |
|-----------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| ID                                | Unique identifier for each customer.                                                                                      |
| LIMIT_BAL                         | Credit limit, representing the maximum amount the customer is allowed to borrow.                                         |
| SEX                               | Gender of the customer (1 = Male, 2 = Female).                                                                            |
| EDUCATION                         | Level of education (1 = Graduate School, 2 = University, 3 = High School, 4 = Others).                                   |
| MARRIAGE                          | Marital status (1 = Married, 2 = Single, 3 = Others).                                                                    |
| AGE                               | Age of the customer.                                                                                                      |
| PAY_0 to PAY_6                    | Payment status for the last six months (PAY_0 = September, PAY_2 = August, ..., PAY_6 = April). Values represent the number of months delayed in payment.|
| BILL_AMT1 to BILL_AMT6            | Amount of bill statement for the last six months. Represents the outstanding balance at the end of each month.            |
| PAY_AMT1 to PAY_AMT6              | Amount of previous payments made in the last six months. Represents the amount paid by the customer in each month.         |
| default.payment.next.month        | Indicates whether the customer will default on the payment next month (1 = Yes, 0 = No).                                 |


## Technical Aspect
This project is divided into two part:
1. Training a [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) classification model to predict defaulter as accurate as possible.
	- Cleaning the datasets, fixing all features
	- Apply Classification ML model
2. Building and deploying a Flask web app.
	- Build the web app using Flask API
	- Upload the project on GitHub
    - Get the customer information from Web app
    - Display the prediction 

## Technologies Used
- Python 
- Data Preprocessing - Numpy , Pandas
- Data Visualization - Seaborn , Matplotlib
- Model Building - Random Forest (Accuracy 84+)
- Connecting ModeL to web - Flask

## Deployment using Render cloud
- https://credit-card-defaulter-prediction-project.onrender.com 

## Credits
- The datasets has been provided by [Kaggle](https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset). The original dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients) at the UCI Machine Learning Repository. This project wouldn't have been possible without this dataset.
 
