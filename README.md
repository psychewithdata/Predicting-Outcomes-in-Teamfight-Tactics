# Predicting-Outcomes-in-Teamfight-Tactics

## Project Overview

This project aims to develop a machine learning model capable of predicting the outcomes of matches in the popular game Teamfight Tactics (TFT). By analyzing and preprocessing game data, various models are trained and evaluated to determine the most effective approach for accurate predictions.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Models Implemented](#models-implemented)
- [Evaluation](#evaluation)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Introduction

The goal of this project is to apply machine learning techniques to predict the outcomes of TFT matches. By leveraging game data, we aim to provide insights into the factors that contribute to winning strategies.

## Dataset

The dataset includes various features from TFT matches such as champion level, specific champions used, items equipped, and other relevant attributes. The data was cleaned and preprocessed before model training.

## Preprocessing

Data preprocessing steps included:
- Encoding discrete and continuous variables
- Handling missing values
- Normalizing features
- Splitting the data into training and test sets

## Models Implemented

The following machine learning models were implemented and evaluated:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Linear Regression
- Support Vector Regression (SVR)

## Evaluation

Models were evaluated based on their performance on the training and test datasets. Key metrics used for evaluation included:
- Training error
- Test error
- Generalization performance

## Key Insights

- Linear Regression and SVR showed the best performance with low errors, indicating strong generalization capabilities.
- SVM exhibited overfitting, suggesting it may not be suitable for this specific prediction task.
- Key predictors of match outcomes include champion level and specific champions/items used.

## Conclusion

The project successfully identified effective machine learning models for predicting TFT match outcomes. Linear Regression and SVR were the most accurate, providing valuable insights into game strategies.

## Future Work

Future improvements to this project could include:
- Incorporating additional features for more comprehensive analysis
- Exploring deep learning models for potentially higher accuracy
- Real-time prediction implementation within the game

## How to Run

1. Clone the repository
2. Install the required dependencies using `pip install -r requirements.txt`
3. Run the preprocessing script: `python preprocess.py`
4. Train the models: `python train_models.py`
5. Evaluate the models: `python evaluate_models.py`
