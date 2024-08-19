# Supervised anomaly detection 
## To identify Credit Card Fraud

This repo has some good example algorithms to do a forensic-type analysis, looking for anomalies and potential fraudulent behavior in a credit card transactions dataset. 

We first do some data cleaning (exclusions, imputation, don't remove outliers - that's what we're looking for), then build variables that are designed to look for the kinds of anomalies we are interested in, in this case, potential fraud transactions.
We compare different ML algortihms for binary classification (fraud/not fraud) like Decision Tree Classifier, Random Forest, Light GBM, and Neural Network Classifier (MLP).