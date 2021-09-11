![credit card](https://user-images.githubusercontent.com/77233162/132944291-bea6e82d-caed-48fa-9f5d-eb75366f123a.jpg)

# Introduction 
When we make any transaction while purchasing any product online, a good amount of people prefer credit cards. The credit limit in credit cards sometimes helps us 
in making purchases even if we don’t have the amount at that time. But these features are often misused by cyber attackers. It is important that credit card companies 
are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. Here comes the need for a system that
can track the pattern of all the transactions and if any pattern is abnormal then the transaction should be aborted.

# Project Overview

In this project,we are going to build a model for detecting fradulent credit card activities. Using a dataset of of nearly 284,807 credit card transactions and 
multiple unsupervised anomaly detection algorithms, we are going to identify transactions with a high probability of being credit card fraud. We will build and 
deploy the following two machine learning algorithms:

- Local Outlier Factor (LOF)
- Isolation Forest Algorithm

# Data Overview

The data fort his project can be downloaded from kaggle: https://www.kaggle.com/mlg-ulb/creditcardfraud

The dataset contains transactions made by credit cards in September 2013 by European cardholders. It contains only numerical input variables which are the result of
a PCA transformation. Due to confidentiality issues, the original features and more background information about the data cannot be provided.Therfore, the features
V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains
the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for 
example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
