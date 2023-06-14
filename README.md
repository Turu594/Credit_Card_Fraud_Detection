# Credit_Card_Fraud_Detection
About Dataset

#Context

The Credit Card Fraud Detection project is used to identify whether a new transaction is fraudulent or not by modeling past credit card transactions with the knowledge of the ones that turned out to be fraud.We will use various predictive models to see how accurate they are in detecting whether a transaction is a normal payment or a fraud.

We are using the datasets provided by Kaggle. This data set includes all transactions recorded over the course of two days. As described in the dataset, the features are scaled and the names of the features are not shown due to privacy reasons.

#Content

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


![image](https://github.com/Turu594/Credit_Card_Fraud_Detection/assets/61057011/22a51318-4d20-40a7-a4c6-4b3aef4f77ba)


![image](https://github.com/Turu594/Credit_Card_Fraud_Detection/assets/61057011/e8e8ea7c-fb3e-4c48-bda6-7e1e4123604d)


![image](https://github.com/Turu594/Credit_Card_Fraud_Detection/assets/61057011/8d168674-4ef7-4cab-96c8-d48a3d3beac7)

![image](https://github.com/Turu594/Credit_Card_Fraud_Detection/assets/61057011/cbf4964f-0680-4ae1-8305-65e06e69abed)

#Conclusion

After performing several models, we have seen that in the balanced dataset with SMOTE technique the RF model has good ROC score and also high Recall. Hence, we can go with the RF model here. It is also easier to interpret and explain to the business.

