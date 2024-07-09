# Heart Attack Risk Prediction
This repository contains the implementation of the Heart Attack Risk Prediction model, which aims to accurately evaluate an individual's likelihood of experiencing a heart attack using advanced data analytics and machine learning techniques.

## Team Members
Aishwarya Kandasamy  
Bhavatarini Thangaraju  
Deepika Alagiriswamy Panneerselvam  
Jude Rosun Jesuraj  
Theepan Kumar Gandhi  

## Introduction
Heart attacks are a significant cause of global mortality, highlighting the necessity for early detection and prevention strategies. Traditional risk assessment methods often overlook subtle yet crucial factors contributing to heart attack risk. This project utilizes machine learning to identify hidden patterns, improve predictive accuracy, and facilitate proactive interventions to reduce the risk of heart attacks.

## Proposed System
The system involves:
- Building a machine learning model for predicting heart attack risk.
- Collecting and preprocessing the dataset.
- Removing the Patient ID column, checking, and removing null and duplicate values.
- Splitting the Blood Pressure column into 'Blood_Systolic_Pressure' and 'Blood_Diastolic_Pressure'.
- Training various machine learning classification algorithms and selecting the most effective one.

## Dataset
Source: Kaggle  
The dataset includes 25 independent variables and one target variable, comprising 8763 patient records.
Important Features
- Age
- Sex
- Cholesterol
- Blood Pressure
- Heart Rate
- Diabetes
- Family History
- Smoking
- Obesity
- Alcohol Consumption
- Exercise Hours Per Week
- Diet
- Previous Heart Problems
- Medication Use
- Stress Level
- Sedentary Hours Per Day
- Income
- BMI
- Triglycerides
- Physical Activity Days Per Week
- Sleep Hours Per Day
- Country
- Continent
- Hemisphere

## Exploratory Data Analysis
Extensive EDA was conducted to understand the data distribution, detect outliers, and identify significant patterns.

## Algorithms Used
1. Logistic Regression
2. Naive Bayes
3. Decision Tree
4. Support Vector Machine (SVM)
5. Random Forest

## Model Evaluation
- Logistic Regression: Accuracy ~ 72.09%
- Naive Bayes: Accuracy ~ 64.18%
- Decision Tree: Accuracy ~ 64.06%
- SVM: Accuracy ~ 64.18%
- Random Forest: Accuracy ~ 70.62%

## Conclusion
The project successfully developed a predictive model capable of accurately assessing individuals' risk of heart attacks. Among the five machine learning algorithms implemented, Logistic Regression achieved the highest accuracy of 72.09%.

## Future Work
- Incorporating more diverse and extensive datasets to enhance the model's predictive power.
- Exploring advanced machine learning techniques, such as deep learning algorithms, to improve accuracy and identify new risk factors.
- Integrating real-time health monitoring devices and genetic information for more personalized risk assessment.
