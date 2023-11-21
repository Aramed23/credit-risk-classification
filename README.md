Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
Overview
The purpose of this analysis is to evaluate the performance of machine learning models in predicting credit risk. 
Results
Accuracy Score: 0.95
Precision Score: 0.88
Recall Score: 0.99
he accuracy score of 0.95 signifies that the model correctly predicted 85% of the instances, reflecting its overall effectiveness.

Precision, which measures the ratio of correctly predicted positive observations to the total predicted positives, is at 0.88. This implies that when the model predicts an applicant as high-risk, it is correct 88% of the time. High precision is essential in a credit risk model to avoid approving loans to potentially risky customers.

The recall score, standing at 0.99, indicates that the model captures 99% of the actual high-risk applicants. A high recall is crucial for identifying and flagging high-risk customers, preventing potential financial losses.
Recommendation
Based on the robust performance metrics, I recommend the adoption of this machine learning model for credit risk assessment by the company. 
