# credit-card-fraud-detection

## Overview
This project aims to develop a machine-learning model for detecting fraud in credit card transactions. A dataset containing a range of credit card transaction characteristics, such as the number of transactions, time, and further relevant information is used to train this model

## problem
A credit card is one of the most used financial products to make online purchases and payments. Though Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.

# PIPELINE OF PROJECT
. import libraries

.understanding the data

.eda

.standard scaling9feature engeniering)

.use smote for imbalce dataset

.split data into train test data

.model traning

.mmodel selection

.hypertuning using gridcv

.perform hypertuning

## Description of Design Choices
### 1. Data Preprocessing
  Handled missing values: Checked for missing data and deleted duplicate rows. No missing values have been found, and a total of 1081 duplicate rows have been deleted.

  Data Imbalance Treatment: To visualize and address the imbalance of classes, used the oversampling technique SMOTE.

Feature Engineering: standard scaling for remove outlier and for better performance

## 2.Model Selection and Hyperparameter Tuning:

Used various classification algorithms such as Logistic Regression, Random Forest, xgBoost have been used.
To improve the model's performance, GridSearchCV was used for hyperparameter adjustment.

## 3.Performance Evaluation of the Model
Evaluated models using key metrics such as accuracy, precision, recall, F1 score, and ROC AUC score.
Model Performance

Logistic Regression : Obtained a f1 score of 12.7% 

Random Forest Classifier: Obtained an f1 score of 83.14% 

xgBoost Classifier: Obtained an f1 score of 82% 

The random forest Obtained the highest ROC AUC score of 83.14% among all models. Hence, the random forest is selected as the best model for credit card fraud detection.

## sucess of model 
we use 3 model for get better result of prediction, with this we got random forest as a better resilt by giving highest f1 score .
acuuracy more than 80%

## Benefits for the Company

Cost Savings: This model helps to prevent financial losses resulting from fraud, by accurately identifying fraudulent transactions. This is to reimburse customers for illegal transactions and to mitigate potential legal and administrative penalties related to fraud cases. Overall, by reducing financial liabilities associated with fraud the model helps to reduce costs.

Enhanced Customer Trust: To strengthen customer trust and confidence in the company's services, efficient detection of fraud is important. The customers are reassured that their financial transactions are secure, leading to a higher level of satisfaction and loyalty. This will allow the company to attract and retain more customers, thereby improving its reputation and market position.

Reduced Operational Risks: Fraudulent activities not only result in the company's financial position but also pose operational risks to the company. Such risks include damage to reputation, legislative scrutiny, and the disruption of operations. The company can proactively mitigate these risks and maintain operational resilience by implementing a robust model for detecting fraud.
