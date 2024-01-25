# Credit-Card-Default-Prediction

## Overview
This is a classification model for a most common dataset, Credit Card defaulter prediction. Prediction of the next month credit card defaulter based on demographic and last six months behavioral data of customers.

## Dataset Information
This dataset contains 25 columns and 3000 rows on information of default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in _Taiwan from April 2005 to September 2005_.

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
 
