# Credit-Card-Fraud-Prediction-Analysis

## Abstract

The increasing prevalence of credit card fraud has posed significant challenges to financial institutions and individuals worldwide. Detecting and preventing fraudulent activities has become crucial to safeguarding the financial well-being of individuals and maintaining the trust and integrity of financial systems. This project aims to conduct a comprehensive analysis of credit card fraud by leveraging data analytics and machine learning techniques. By examining historical transaction data and applying advanced algorithms, we seek to identify patterns, anomalies, and indicators of fraudulent behavior, enabling timely detection and proactive fraud prevention measures. The insights gained from this analysis will contribute to strengthening security measures and enhancing the efficiency of fraud detection in the financial industry.

## Introduction

Credit card fraud has become a pressing issue as the reliance on electronic payment systems grows. Criminals employ sophisticated techniques, exploiting vulnerabilities to carry out fraudulent activities, resulting in substantial financial losses for individuals, businesses, and financial institutions. Traditional rule-based fraud detection methods often struggle to keep pace with evolving fraud tactics. Therefore, there is a need for advanced analytics and machine learning approaches to effectively combat credit card fraud.

This project aims to develop a credit card fraud analysis system that leverages historical transaction data to identify fraudulent patterns and anomalies. By applying machine learning algorithms and predictive models, we aim to create a proactive system capable of detecting fraudulent activities in real-time or near real-time. Additionally, we will explore various feature engineering techniques and model selection methods to optimize the accuracy and efficiency of the fraud detection system.

Through this project, we seek to address the following key objectives:

♦ Analyze historical credit card transaction data to understand patterns and characteristics of fraudulent transactions.

♦ Develop and implement machine learning models to detect anomalies and identify potential fraudulent activities.

♦ Evaluate the performance of different algorithms and techniques for fraud detection, considering factors such as accuracy, precision, recall, and computational efficiency.

♦ Investigate the effectiveness of incorporating additional data sources, such as customer behavior patterns, geo-location data, or social network analysis, to enhance fraud detection capabilities.

♦ Provide insights and recommendations for financial institutions to improve their fraud prevention strategies and strengthen security measures.

♦ By conducting a comprehensive analysis of credit card fraud, this project aims to contribute to the ongoing efforts in mitigating financial risks, protecting  individuals and businesses from fraud, and enhancing the overall security of electronic payment systems.



## Overview of the Code


![credit_card_frauds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2015/12/credit-card-fraud.jpg)

1. ## Exploratory Data Analysis

♦ Loading data
 
♦ Printing data overview

♦ Printing numerical summary for Time and Amount columns

♦ Plotting distribution of Time 

♦ Plotting distribution of Amount 

♦ Counting number of fraud vs non-fraud transactions and displaying them with their ratio

♦ Plotting count of fraud vs non-fraud transactions in a bar chart

2. ## Data Processing

♦ Plotting heatmap to find any high correlations between variables

3. ## Model Building

♦ Drop the 'Class' column to prepare data for splitting

♦ Get the target variable

♦ Split data into training, validation and test sets, ensuring the class distribution is maintained

♦ Initialize the StandardScaler object and fit it to the training data

♦ Scale the training, validation, and test sets using the scaler

♦ Modeling Techniques

1. ## Logistic Regression

♦ Calculated Precision score,recall score,F1 scores of the datasets

2. ## Ensemble Techniques

♦ XG Boost classifer 

♦  Decision Tree

♦ Calculated Precision score,recall score,F1 scores of the datasets

4. Random Forest

♦ Calculated Precision score,recall score,F1 scores of the datasets

5. ## References

Kaggle Dataset: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
