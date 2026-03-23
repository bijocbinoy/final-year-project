# Mental Health Treatment Behaviour Analysis using Machine Learning

## Overview

This project applies machine learning techniques to analyse and understand mental health treatment-seeking behaviour using survey data. The goal is to identify key factors influencing whether individuals seek mental health support and to compare the performance of different models.



## Objectives
- Predict mental health treatment-seeking behaviour
- Compare multiple machine learning models
- Identify key influencing factors
- Apply explainable AI techniques (EXP(B) and SHAP)



## Dataset
- Source: OSMI Mental Health Survey
- Type: Structured (tabular) dataset
- Size: 1250 samples, 120+ features
- Features include:
 - Demographics (Age, Gender)
 - Workplace factors
 - Mental health history


## Methodology

1️. Data Preprocessing
 - Data cleaning
 - Handling missing values
 - One-hot encoding
 - Train-test split (80/20)
 - Feature scaling (for Neural Network)



2️. Models Used
 - Logistic Regression
 - Random Forest
 - XGBoost
 - Neural Network (MLP)



3️. Evaluation Metrics
 - Accuracy
 - Precision
 - Recall
 - F1-score
 - Confusion Matrix

## Results
|Model     |     Accuracy  |
|:-----------|----------------:|
|Logistic Regression| 0.848|
|Random Forest| 0.808|
|XGBoost |0.804|
|Neural Network| 0.776|

## Explainability

### Logistic Regression
 - Used EXP(B) (Odds Ratio)
 - Identified key predictors:
   - Work interference
   - Family history
   - Care options

### SHAP (Random Forest)
 - Identified important features
 - Explained model predictions
 - Captured feature interactions

 ## Neural Network Observation
	- Accuracy remained 77% across architectures
	- Model converged early
	- Limited improvement due to small dataset size

## Author
- Bijo Cheriyan Binoy
- MSc Data Science
- University of Hertfordshire

## Final Note
This project demonstrates how combining machine learning with explainability techniques can provide meaningful insights into mental health behaviour.
