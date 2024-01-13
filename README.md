# online-payment-fraud-detection-model

# Problem Statement:

In the rapidly evolving landscape of digital transactions, the prevalence of online payment fraud has become a significant concern for businesses and consumers alike.
To tackle this problem devloped an Online Payment Fraud Detection model.

# Objective:

Purpose of this Project to predict whether a payment is fraud or not based on the input parameters like payment type, 
payment amount, nameOrig, oldbalanceOrg,newbalanceOrig, oldbalanceDest, newbalanceDest etc. Each row in the data provides relavant information about the payment transaction. Throughout this Project i have followed the whole life cycle of a Data Science Project as:

EDA(Exploring Data and Understanding features doing univariate analysis,Bivariate analysis,Finding Distribution) and Data Cleaning(Finding Types of Features,Duplicate values,Missing Values,Outlier Detection)
Feature Engineering((Imputting Missing Values,Outlier,handlingImbalanced)) and Feature Selection ,Feature Scaling
Model Selection
Model Building
Model HyperParameter Tuning
Model Evaluation(Testing)


# Tools and Technologies Used :

Python,Machine Learning,Sklearn,Pandas,Matplotlib,Seaborn,Numpy

# Data Collection:

I have gathered dataset from open government data website for this project.

# EDA:

Perform eda on dataset to derive some conclusion and insights which could further in model building.

# Feature Engineering:

Impute Missing values,handle ouliers,removing duplicates values.

# Feature Selection:

Perform feature selection using correlation matrix and tried to know which feature is impacting much to my target variable.

# Model selection and building:

used various machine learning algorithms(Logistic Regression ,Decision tree,Random forest,XGBoost) and tried to know which best suite on my dataset.


# Model Tuning
perform hyperparameter tuning on Decision tree and achieved accuracy 93%.

# Model Tesing:

perform model testing on unseen data.

# Model Deployment:
save the model and loaded it Pycharm to delpoy it.
