![logo](https://github.com/Dhruv3004/Heart-Disease-Prediction/blob/main/1_CQXQxHDKi0Q2IpdjhufEcw.jpg?raw=true)

## Heart Disease Prediction
This project aims to predict the presence of heart disease in patients using a variety of clinical and demographic features. The dataset includes various attributes collected from patients, which are used to train and evaluate a machine learning model.

## Table of Contents
Project Overview
Dataset Description
Features
Modeling

## Project Overview
Heart disease is one of the leading causes of death worldwide. Early prediction and diagnosis can significantly improve patient outcomes. This project uses machine learning algorithms to predict the likelihood of heart disease in a patient based on several clinical and demographic factors.

## Dataset Description
The dataset used in this project contains various features related to patient health, including age, sex, cholesterol levels, and more. The target variable is a binary classification indicating the presence (1) or absence (0) of heart disease.

## Features
The dataset contains the following features:

age: Age of the patient in years.
sex: Gender of the patient (1 = male, 0 = female).
cp: Chest pain type:
0: Typical angina
1: Atypical angina
2: Non-anginal pain
3: Asymptomatic
trestbps: Resting blood pressure in mm Hg on admission to the hospital.
chol: Serum cholesterol level in mg/dl.
fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
restecg: Resting electrocardiographic results:
0: Normal
1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
thalach: Maximum heart rate achieved.
exang: Exercise induced angina (1 = yes, 0 = no).
oldpeak: ST depression induced by exercise relative to rest.
slope: The slope of the peak exercise ST segment:
0: Upsloping
1: Flat
2: Downsloping
ca: Number of major vessels (0-3) colored by fluoroscopy.
thal: Thalassemia blood disorder (0 = error, 1 = fixed defect, 2 = normal, 3 = reversible defect).
target: The presence of heart disease (0 = no disease, 1 = disease).

## Modeling
The project involves training a machine learning model using the features listed above to predict the target variable. Various algorithms can be explored, including logistic regression, decision trees, random forests, and more. The performance of the models will be evaluated using metrics such as accuracy, precision, recall, and F1-score.
