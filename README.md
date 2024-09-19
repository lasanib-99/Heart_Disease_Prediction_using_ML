# Heart_Disease_Prediction_using_ML
Predicting the existence of heart disease using machine learning techniques such as SVC, KNN, Decision Trees, Logistic Regression, and Naïve Bayes, utilizing a combined dataset from multiple sources.

# Heart Disease Prediction using Machine Learning

This project aims to develop a machine learning-based predictive model to diagnose the existence of heart disease. It leverages data from various sources and uses multiple classification algorithms to provide insights and predictions that can assist in early diagnosis.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Key Features](#key-features)
- [Results](#results)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [License](#license)

## Introduction
Heart disease, also known as cardiovascular disease (CVD), is a major cause of morbidity and mortality globally. This project uses machine learning classification algorithms to predict the presence of heart disease based on key health metrics. The dataset is a combination of five popular heart disease datasets curated into one.

## Dataset
The dataset consists of various health indicators, including:
- **Age**: Patient's age
- **Sex**: Gender (1 = male, 0 = female)
- **Chest Pain Type**: Different types of chest pain experienced
- **Resting Blood Pressure**: Blood pressure in mm Hg
- **Serum Cholesterol**: Cholesterol level in mg/dl
- **Fasting Blood Sugar**: Whether blood sugar > 120 mg/dl
- **Resting ECG**: Resting Electrocardiogram results
- **Maximum Heart Rate**: Maximum heart rate achieved
- **Exercise-Induced Angina**: Angina induced by exercise
- **Old Peak**: ST depression by exercise relative to rest
- **Slope**: Slope of the peak exercise ST segment
- **Target**: Presence of heart disease (1 = disease, 0 = normal)

### Dataset Source:
[Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/mexwell/heart-disease-dataset)

## Objectives
- Develop the best-fit predictive model using machine learning to accurately predict heart disease.
- Identify significant variables in predicting heart disease.
- Investigate relationships between feature variables and their impact on heart disease prediction.

## Methodology
The project follows these steps:
1. Data Preprocessing (handling missing values, normalization)
2. Exploratory Data Analysis (EDA)
3. Model Development (using SVC, KNN, Decision Trees, Logistic Regression, and Naïve Bayes)
4. Cross-validation and Hyperparameter tuning
5. Model Evaluation (accuracy, precision, recall, F1-score)
6. Interpretation of Results

## Key Features
- **Support Vector Classification (SVC)**: SVM-based classification model.
- **K-Nearest Neighbors (KNN)**: Distance-based classification model.
- **Decision Trees**: Tree-based classification.
- **Logistic Regression**: Regression-based classification.
- **Naïve Bayes**: Probability-based classification model.

## Results
The model evaluation indicates that LR, SVM and GNB perform best, with an accuracy around 85%. The results are consistent across multiple validation techniques.

### Folder Details:
- **Dataset**: Contains the heart disease dataset.
- **Proposal**: The project proposal outlining the objectives and methodology.
- **Notebook**: Jupyter notebook containing code for data analysis, model training and evaluation.
- **Reports**: Final report detailing the project results, findings and conclusions.
