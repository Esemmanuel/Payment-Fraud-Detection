# Payment-Fraud-Detection
Detect Fraudulent transactions in a large dataset.

# Online Payments Fraud Detection
Fraud detection is critical for any bank or financial institution. As a result, it is critical to investigate models for detecting fraudulent transactions in large amounts of data.
In this machine learning project, we use logistic regression and random forest algorithms to detect online payment fraud transactions. We build these binary classifiers and test them with the various machine learning techniques mentioned above to see which one fits best.

# Data Description

The given dataset contains 1048575 rows, 10 columns, and no missing values. Exploratory data analysis was used to better understand the dataset and gain some important insights. SMOTE was used to balance the dataset after it was discovered to be imbalanced.
The goal of this project is to create two distinct models capable of predicting online payment fraud.
Finally, the model was evaluated based on the recall, precision, and accuracy scores.


# Columns

The below column reference:

- step: represents a unit of time, with 1 step equaling 1 hour.
- amount: the amount of the transaction. 
- nameOrig: customer initiating the transaction. 
- oldbalanceOrg: balance before the transaction.
- newbalanceOrg: balance after the transaction.
- nameDest: the transaction's recipient. 
- oldbalanceDest: the recipient's initial balance before the transaction. 
- newbalanceDest: the recipient's new balance after the transaction.
- isFraud: a fraud transaction.


# Steps taken for this Project
- Loaded the dataset.
- Inspect the dataset( checked the information, null values, statistical description, total number of fraudulent and non-fraudulent transactions).
- Dropped irrelevant coumns( ‘nameOrig’, ‘nameDest’).
- Carried out EDA and visualization for important insights.
- Carried out One-Hot-Encoding to convert categorical data to numerical.
- Carried out standard scaling.
- Selected target and features.
- Splitted the dataset to a ratio of 80-20 using the train-test split.
- Initialized machine learning algorithms
- Trained and tested the models.
