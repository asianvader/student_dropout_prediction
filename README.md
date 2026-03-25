# Project: Predicting Student Dropout with Supervised Learning

An end-to-end machine learning project exploring student dropout risk using supervised learning models across multiple stages of the student journey.

## Overview

This project investigates how machine learning can be used to identify students at risk of dropping out.

Student retention is an important challenge in education. Early identification of at-risk students can support better interventions, improve student outcomes, and help institutions make more informed decisions. This project uses anonymised project materials to demonstrate a full machine learning workflow for dropout prediction.

The analysis is structured in three stages:

1. **Applicant and course information**
2. **Student engagement data**
3. **Academic performance data**

This staged approach reflects how student information typically becomes available over time and allows comparison of predictive performance at different points in the student lifecycle.

## Objective

The objective of this project is to build and compare supervised learning models that predict whether a student will drop out.

The project includes:

- exploratory data analysis
- data preprocessing
- feature engineering
- model development
- model evaluation
- interpretation of results and recommendations

## Problem Statement

Using historical student data, develop models that predict dropout risk and assess how predictive performance changes across different stages of the student journey.

Key questions addressed:

- How accurately can dropout be predicted at each stage?
- Which variables are most useful for identifying at-risk students?
- At what stage is intervention likely to be most effective?

## Project Workflow

### 1. Data Exploration
- inspect dataset structure and feature types
- assess missing values
- analyse the target variable
- compare patterns across stages

### 2. Data Preprocessing
- clean and standardise data
- handle missing values
- encode categorical variables
- scale numerical variables where required
- remove low-value or highly sparse features

### 3. Feature Engineering
- create derived variables where useful
- test whether engineered features improve predictive performance

### 4. Model Development
The project compares supervised learning approaches including:

- **XGBoost**
- **Neural Network**

### 5. Model Evaluation
Models are evaluated using classification metrics such as:

- accuracy
- precision
- recall
- ROC-AUC

### 6. Interpretation
- identify the most informative predictors
- compare performance across stages
- assess where early intervention may have the most value
- summarise practical recommendations

## Repository Contents

This repository includes:

- `student_dropout_prediction.ipynb` — the project notebook
- `student_dropout_report.pdf` — the written report

## Confidentiality Note

This repository contains an anonymised version of the project.

To respect NDA and confidentiality requirements:

- organisation names have been removed
- proprietary business context has been generalised
- sensitive fields, labels, and references may be renamed or redacted
- parts of the notebook and report have been modified to remove confidential information
- the original dataset is **not included**

The focus of this repository is to demonstrate the project approach, modelling workflow, and analytical reasoning without disclosing proprietary information.

## Tools and Libraries

This project uses the following tools and libraries:

- **Python**
- **pandas** for data manipulation and analysis
- **NumPy** for numerical operations
- **Matplotlib** and **Seaborn** for data visualisation
- **scikit-learn** for preprocessing, imputation, train/test splitting, hyperparameter tuning, and evaluation
- **XGBoost** for gradient boosting classification
- **TensorFlow / Keras** for neural network modelling
- **Keras Tuner** for neural network hyperparameter tuning

Key components used include:

- `OrdinalEncoder`
- `StandardScaler`
- `SimpleImputer`
- `train_test_split`
- `GridSearchCV`
- `accuracy_score`
- `confusion_matrix`
- `precision_score`
- `recall_score`
- `roc_auc_score`
- `roc_curve`
- `precision_recall_curve`
- `auc`
- `Sequential`
- `Dense`
- `Dropout`
- `Input`
- `Adam`
- `EarlyStopping`

The project was developed in a notebook-based workflow using Jupyter/Colab-style experimentation.

## Skills Demonstrated

- supervised machine learning
- classification modelling
- feature engineering
- data preprocessing
- model evaluation
- comparative analysis
- business-focused interpretation of ML outputs

## Summary

This project demonstrates how supervised learning can be applied to a student retention problem using staged data, practical modelling techniques, and results interpretation oriented toward decision-making.