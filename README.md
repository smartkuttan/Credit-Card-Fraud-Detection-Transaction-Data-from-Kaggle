# Credit-Card-Fraud-Detection-Transaction-Data-from-Kaggle
The aim of this project is to predict fraudulent credit card transactions using machine learning models.  The data set that was provided to during this project was obtained from Kaggle. It contains thousands of individual transactions that took place over a course of two days and their respective labels.
A. Data Collection Phase 
The Real World credit card transactions dataset is provided from the Kaggle website by Upgrad The dataset contains transactions of European cardholders. There are a total of 2, 84,807 transactions, out of which 492 are fraud ones. It contains 31 features out of which 28 numerical input variables are obtained by the transformation of PCA method and two features Time and Amount that is not transformed. The last feature Class is the response variable and it takes value 1 as fraud and value 0 as non-fraud. . This dataset is highly unbalanced. Since providing transaction details of a customer is considered to issue related to confidentiality, therefore most of the features in the dataset are transformed using principal component analysis (PCA). V1, V2, V3,..., V28 are PCA applied features and rest i.e., ‘time’, ‘amount’ and ‘class’ are non-PCA applied features,

S. No.	Feature	Description
1.	Time	Time in seconds to specify the elapses between the current transaction and first transaction.
2.	Amount	Transaction amount
3.	Class	0 - not fraud

1 – fraud


