# Wine Quality Prediction

## Overview

This project focuses on predicting wine quality using Machine Learning techniques. The dataset is preprocessed, standardized, and used to train both a custom Decision Tree implementation and Scikit-learn's Decision Tree Classifier.

The objective is to compare the performance of a manually implemented Decision Tree with an industry-standard machine learning library implementation.

## Dataset

* Dataset: Red Wine Quality Dataset
* Source: UCI Machine Learning Repository
* Samples: 1,599 red wine records
* Features: 11 physicochemical attributes
* Target: Wine Quality

The target variable was converted into a binary classification problem:

* Good Quality (Quality ≥ 6)
* Poor Quality (Quality < 6)

## Features Used

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

## Methodology

1. Data Preprocessing
2. Feature Standardization
3. Train-Test Split
4. Custom Decision Tree Implementation
5. Scikit-learn Decision Tree Training
6. Performance Evaluation
7. Confusion Matrix Analysis

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

## Models Implemented

### Custom Decision Tree

* Gini Impurity Calculation
* Recursive Tree Construction
* Manual Prediction Pipeline

### Scikit-learn Decision Tree

* DecisionTreeClassifier
* Gini Criterion
* Depth-Limited Tree

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Project Structure

* wine-quality-prediction.ipynb
* README.md

## Learning Outcomes

* Understanding Decision Tree internals
* Gini Impurity calculations
* Tree-based classification
* Performance comparison between custom and library implementations
* Machine Learning workflow design
