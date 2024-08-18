# Predicting Heart Disease Using Machine Learning

This project aims to use various Python-based machine learning and data science libraries to build a model capable of predicting whether or not a patient has heart disease based on their medical attributes.

## Table of Contents
1. Problem Definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation
7. Feature Importance


## 1. Problem Definition

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 2. Data

The dataset used for this project is the Cleavland dataset from the UCI Machine Learning Repository. It contains clinical attributes related to heart disease diagnosis.

- [UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- [Kaggle Version of the Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)

## 3. Evaluation

The goal is to build a machine learning model that achieves at least **95% accuracy** in predicting whether or not a patient has heart disease.

## 4. Features

The dataset contains the following features:

- **age**: Age of the patient in years
- **sex**: Gender (1 = male, 0 = female)
- **cp**: Chest pain type (4 values)
  - 0: Typical angina
  - 1: Atypical angina
  - 2: Non-anginal pain
  - 3: Asymptomatic
- **trestbps**: Resting blood pressure (mm Hg)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar (> 120 mg/dl) (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (3 values)
  - 0: Normal
  - 1: ST-T wave abnormality
  - 2: Possible or definite left ventricular hypertrophy
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (3 values)
  - 0: Upsloping
  - 1: Flat
  - 2: Downsloping
- **ca**: Number of major vessels colored by fluoroscopy (0-3)
- **thal**: Thalassemia (3 values)
  - 1,3: Normal
  - 6: Fixed defect
  - 7: Reversible defect
- **target**: Diagnosis of heart disease (1 = yes, 0 = no)

## 5. Modelling

The modelling process involves splitting the data into training and test sets, training various machine learning models, and evaluating their performance. The current implementation uses a simple train-test split, but further experimentation is planned.

### Steps:
1. Split the data into features (`X`) and target (`y`).
2. Split the data into training and test sets.
3. Train machine learning models on the training data.
4. Evaluate model performance on the test data.

## 6. Experimentation
Further experimentation and improvement options include:

Collecting more data to enhance the model's performance.
Trying advanced models such as CatBoost or XGBoost.
Fine-tuning the current models to improve accuracy.

## 7. Feature Importance
Understanding which features contribute the most to model predictions is crucial. Feature importance will guide further data collection and model improvements.

Feature importance analysis varies for each machine learning model and will be explored in this project to ensure the most influential features are properly accounted for.

### Conclusion
This project aims to leverage machine learning techniques to predict heart disease, which can be pivotal in early diagnosis and preventive healthcare.
