# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Purpose of the Analysis:
The goal was to predict loan status (whether a borrower will default or not) based on financial data.

Financial Information & Prediction:
The dataset included variables such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable was loan_status (0 = not defaulted, 1 = defaulted).

Target Variable Overview:
A quick check with value_counts() would show the distribution of default vs. non-default loans.

Machine Learning Process:
Data Preparation: Separated features (X) and target (y).
Train-Test Split: Split data into training (80%) and testing (20%) sets.
Model Training: Used Logistic Regression to learn patterns in the training data.
Prediction & Evaluation: Evaluated model performance using a confusion matrix and classification report.
Methods Used:
LogisticRegression: Chosen for binary classification.
train_test_split: To divide data for training/testing.
confusion_matrix, classification_report: To assess accuracy, precision, and recall.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1: Logistic Regression
 * Accuracy: 99% – The model correctly classified the majority of loan statuses.
 * Precision (for defaults - 1): 86% – 86% of predicted defaults were actually defaults.
 * Recall (for defaults - 1): 91% – 91% of actual defaults were correctly identified.
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Since only one model was tested (Logistic Regression), it is currently the best. Performance is high, but if we were to compare multiple models, we would look at recall for 1s, accuracy, and F1-score to determine the best performer.
* Yes. If predicting loan defaults (1s) is the priority (e.g., to minimize financial risk), recall for 1s is more important—meaning we should focus on reducing false negatives. If predicting non-defaults (0s) is key (e.g., approving more safe loans), precision for 0s would matter more.
* Random Forest or Decision Tree, to compare results
If you do not recommend any of the models, please justify your reasoning.

