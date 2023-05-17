# Credit-card-fraud-prediction-analysis
Overview of the Code


![credit_card_frauds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2015/12/credit-card-fraud.jpg)

1. Exploratory Data Analysis

♦ Loading data
 
♦ Printing data overview

♦ Printing numerical summary for Time and Amount columns

♦ Plotting distribution of Time 

♦ Plotting distribution of Amount 

♦ Counting number of fraud vs non-fraud transactions and displaying them with their ratio

♦ Plotting count of fraud vs non-fraud transactions in a bar chart

2. Data Processing

♦ Plotting heatmap to find any high correlations between variables

3. Model Building

♦ Drop the 'Class' column to prepare data for splitting

♦ Get the target variable

♦ Split data into training, validation and test sets, ensuring the class distribution is maintained

♦ Initialize the StandardScaler object and fit it to the training data

♦ Scale the training, validation, and test sets using the scaler

♦ Modeling Techniques

1. Logistic Regression

♦ Calculated Precision score,recall score,F1 scores of the datasets

2. Ensemble Techniques

♦ XG Boost classifer 

4.Decision Tree

♦ Calculated Precision score,recall score,F1 scores of the datasets

4. Rabdom Forest

♦ Calculated Precision score,recall score,F1 scores of the datasets

5.References

Kaggle Dataset: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
