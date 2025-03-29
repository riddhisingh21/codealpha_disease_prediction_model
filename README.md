# Disease Prediction Model

## Overview:
This project aims to develop a predictive model that can identify diseases based on patient symptoms and demographic information. The model utilizes a dataset containing various medical records, including symptoms, age, gender, blood pressure, cholesterol levels, and diagnosis outcomes.

## Dataset:
The dataset used in this project is a comprehensive collection of disease symptoms and patient profiles. It includes the following columns:
- Disease: Name of the medical condition.
- Fever: Indicates whether the patient has a fever (Yes/No).
- Cough: Indicates whether the patient has a cough (Yes/No).
- Fatigue: Indicates whether the patient experiences fatigue (Yes/No).
- Difficulty Breathing: Indicates whether the patient has difficulty breathing (Yes/No).
- Age: Age of the patient in years.
- Gender: Gender of the patient (Male/Female).
- Blood Pressure: Blood pressure level of the patient (Low/Normal/High).
- Cholesterol Level: Cholesterol level of the patient (Normal/High).
- Outcome Variable: Result of the diagnosis or assessment for the specific disease (Positive/Negative).

## Problem Statement:
Given a set of symptoms and patient characteristics, we aim to predict whether a patient is likely to have a specific disease. This can aid healthcare professionals in diagnosing conditions more efficiently.

## Methodology:
- Data Preprocessing: The dataset is cleaned and preprocessed by encoding categorical variables into numerical format using Label Encoding.
- Feature Selection: Features are selected based on their relevance to disease prediction.
- Model Training:
  A Random Forest Classifier is trained with hyperparameter tuning using Grid Search for optimal performance.
  A Gradient Boosting Classifier is also implemented for comparison.
- Model Evaluation: The models are evaluated using metrics such as accuracy, confusion matrix, and classification report. Cross-validation scores are also calculated to ensure robustness.

## How to Use
- Clone or download this repository.
- Open the Kaggle notebook in your Kaggle environment.
- Ensure that you have access to the dataset by placing it in the appropriate directory in your Kaggle environment.
- Run all cells in the notebook sequentially to preprocess data, train models, and evaluate performance.

## Results
The models' performance is evaluated based on accuracy and other metrics. The best parameters for the Random Forest model are displayed along with performance metrics for both models.
