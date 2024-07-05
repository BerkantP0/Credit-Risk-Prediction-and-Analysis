# Credit Risk Estimation and Analysis using Machine Learning <div/>
This repository contains code for predicting credit risk using machine learning techniques. The project focuses on analyzing a dataset to build a predictive model for loan status.

## Dataset
The dataset used in this project is sourced from Kaggle, titled [Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset). It includes various features related to loan applicants and their loan status.

## Project Overview
The project involves several steps:

1.Data Cleaning and Preprocessing:

 • Loading the dataset (credit_risk_dataset.csv) into a Pandas DataFrame.
 • Checking for missing values and dropping rows with missing data.
 • Encoding categorical variables using one-hot encoding.

2.Exploratory Data Analysis (EDA):<div/>
 
 • Visualizing the distribution of loan status.
 • Examining feature correlations using a heatmap.

3.Model Building:<div/>

 • Splitting the dataset into training and testing sets.
 • Training a Random Forest Classifier on the training data.
 • Evaluating the model using accuracy, ROC-AUC score, and F1 score on the test set.

4.Hyperparameter Tuning:<div/>

• Performing a grid search using cross-validation to optimize model parameters (number of estimators, maximum depth, and minimum samples split).
• Selecting the best model based on ROC-AUC score.

5.Feature Importance:<div/>

• Visualizing feature importances of the best model using a bar plot.

# Requirements

Python 3.x
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
