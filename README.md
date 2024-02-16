# Logistic Regression

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this Analysis is to build a machine-learning program to create models and predict creditworthiness to find which loans are low-risk and high-risk
* The focal financial data is the loan status. Several features from the financial dataset, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt are all used to generate a prediction.
* The Target value of "value_counts" is checking and finding the balance of each loan status. 0(low-risk) with a count of 75036 and 1(high-risk) with a count of 2500, means the loans trend high risk
* Machine Learning Process Steps
	* Created label sets
	* Split the data into training and testing sets with train_test_split
	* Made 2 Models LogisticRegression and RandomOverSampler
	* Made predictions of the fitted models
	* Analyzed the data given by the models

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
	 * Accuracy: 0.95
	 * Precision: 1.00, high-risk 0.85
	 * Recall: 0.99, high-risk 0.91

* Machine Learning Model 2:
	 * Accuracy: 0.99
	 * Precision: 0.99, high-risk 0.99
	 * Recall: 0.99, high-risk 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The random over sampled model seemed to fit better with the given data as it has better accuracy,recall and precision scores in both ends.
* Yes the preformance is effected by the problem trying to be solved, for a problem like this i would recomend the random over sampled model as the number of false postives is lower than the alternatives.
