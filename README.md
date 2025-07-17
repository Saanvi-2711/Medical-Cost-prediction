# Medical-Cost-Prediction
This project is a beginner-friendly implementation of a supervised machine learning task using linear regression to predict a person’s annual medical expenses based on various personal and demographic features which is demonstrated and developed in Google Colab.

Note: This project was created purely for learning purposes and to understand the machine learning workflow end-to-end.

## Problem Statement

ACME Insurance Inc. wants to automate the prediction of medical costs based on:
*	Age
*	Sex
*	BMI
*	Number of children
*	Smoking status
*	Region of residence

This model will help determine insurance premiums in a way that’s interpretable and compliant with regulations.

## Dependencies

This project was built using the following Python libraries:
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

## Technical Implementation

This project demonstrates the complete end-to-end machine learning workflow using a linear regression model.

1. Data Loading & Exploration
*	Loaded the dataset using pandas
*	Checked for missing values, data types, and basic statistics
*	Performed exploratory analysis:
*	Correlation matrix
*	Distribution plots
*	Feature-target relationships

2. Data Preprocessing
*	Encoded categorical variables (sex, smoker, region) using one-hot encoding and label encoding
*	Split the dataset into features (X) and target (y = charges)
*	Created training and validation datasets using train_test_split

3. Model Building
*	Used LinearRegression from scikit-learn to build the model
*	Fitted the model on the training set
*	Extracted model coefficients and intercept for interpretation

4. Model Evaluation
*	Evaluated performance using:
*	Root Mean Squared Error (RMSE)
*	Compared training vs validation performance

5. Model Interpretation
*	Analyzed the learned coefficients to understand:
*	Which features increase or decrease medical costs
*	How strongly each feature affects the outcome
