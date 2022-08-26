# Credit Card Customer Churn Analysis
A Predictive Analysis on Credit Customer Churn Using Machine Learning and Ensemble Techniques. 

## Overview
Customer relationship management and customer churn prediction have received growing attention over the past decade. The aim of this research is to develop and compare predictive models to detect credit card customer attrition in order to better help financial institutions reduce the severity of loss to their businesses incurred by customers exiting the company. Machine Learning techniques such as Random Forest, Support Vector Machine, K-Nearest Neighbours, XGBoost and Artificial Neural Networks, as well as Ensemble techniques such as Stacking using Logistic Regression as a meta-learner and Voting are leveraged to classify credit card customer churn. We experiment by appplying class balancing techniques such a SMOTE and stratified random sampling to improve the performance of the models.


## Dataset
The Dataset is available on Kaggle at https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers

The Dataset was originally obtained from Analyttica Datalab Inc, a Data Analytics and AI Solution Company, which provides real business cases, while retaining the privacy of the company

It consist of 10,127 credit card consumer observations. All customers in the dataset have been with the bank for at least 12 months. After the data clean-up and pre-processing, the dataset is made up of 20 predictor variables and a target variable to indicate a customer’s decision to leave or remain with the credit card provider

## Results

We were able to significantly improve the recall score by applying SMOTE balancing technique. Overall, XGBoost classifier and Stacking Ensemble outperformed all other models

A detailed report of the anaylis can be found at [Credit Card Customer Churn Report.pdf](https://github.com/Didi-Ojo/Credit-Card-Customer-Churn-Analysis/blob/main/Credit%20Card%20Customer%20Churn%20-%20Final%20Report.pdf)
