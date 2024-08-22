
# Credit Card Approval Prediction Using Machine Learning

## Project Overview

This project focuses on predicting credit card approval using various machine learning models. The goal is to analyze and predict whether an individual’s credit card application will be approved based on historical data. The models used include Logistic Regression, Decision Tree, Random Forest, XGBoost, LightGBM, CatBoost, and SVM.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Feature Engineering](#feature-engineering)
  - [Response Variable](#response-variable)
  - [Features](#features)
    - [Binary Features](#binary-features)
- [Modeling](#modeling)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Selection](#model-selection)
  - [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Dataset

The dataset used in this project comprises records of applicants, including their demographics, financial information, and previous credit history. The data is divided into two parts:
1. `application_record.csv`: Contains the personal information of applicants.
2. `credit_record.csv`: Contains the credit history and records of applicants.

## Feature Engineering

### Response Variable
The response variable is the target outcome of whether a credit card application is approved or not.

### Features
The features used in this project include various demographic and financial indicators such as age, income, gender, and previous credit history. Features are categorized as binary, categorical, and continuous.

#### Binary Features
- Gender
- Owning a car
- Owning a house
- Having a phone
- Having an email
- Having a work phone

## Modeling

### Data Preprocessing
Data preprocessing involves handling missing values, encoding categorical variables, and normalizing the data. Techniques such as SMOTE (Synthetic Minority Over-sampling Technique) are used to address class imbalance in the dataset.

### Model Selection
Several machine learning models are trained and compared in this project, including:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Support Vector Machine (SVM)

### Evaluation Metrics
The models are evaluated based on accuracy, confusion matrix, and other relevant metrics to determine the best-performing model.

## Results

The model performance is compared, and the CatBoost classifier achieved the highest accuracy of 0.89459 on the test dataset.

## Installation

To install the required libraries, run the following commands:

```bash
pip install -U imbalanced-learn
pip install xgboost
pip install lightgbm
pip install catboost
```

## Usage

To use this notebook:

1. Clone the repository or download the notebook.
2. Install the required packages using the commands provided in the Installation section.
3. Run the Jupyter Notebook to train the models and make predictions.

