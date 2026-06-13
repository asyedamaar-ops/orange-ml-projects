# Titanic Survival Prediction using Orange 3

A binary classification project predicting passenger survival on the Titanic, built as a visual workflow in Orange 3.

## Problem Statement

Given passenger attributes (such as class, age, sex, and fare), predict whether a passenger survived the Titanic disaster. This is a classic introductory classification problem used to demonstrate end-to-end ML workflow design — from raw data to evaluated model.

## Dataset

- **Source**: Titanic passenger dataset (commonly used for classification benchmarking)
- **Target variable**: Survived (Yes/No)
- **Features**: Passenger class, sex, age, fare, and other demographic/ticket attributes

## Workflow Overview

The Orange workflow (`Titanic_orange_assign.ows`) follows this pipeline:

1. **File** → loads the Titanic dataset
2. **Data Table** → inspect the raw data and check for missing values
3. **Select Columns** → choose target (Survived) and relevant predictor features
4. **Preprocess** → handle missing values, normalize numeric features, encode categorical variables
5. **Visualization**:
   - **Box Plot** → distribution of features (e.g., fare, age) across survival outcomes
   - **Distributions** → feature distributions by class
   - **Scatter Plot** → relationships between numeric features
6. **Logistic Regression** → trains a classifier to predict survival
7. **Test and Score** → evaluates the model using cross-validation
8. **ROC Analysis** → visualizes the trade-off between true positive and false positive rates to assess classifier performance

## Approach

Logistic Regression was chosen as a simple, interpretable baseline well-suited to binary classification problems. It provides direct insight into how each feature (e.g., passenger class, sex, fare) influences survival probability, while the ROC Analysis widget helps assess overall discriminative power independent of a fixed classification threshold.

## Files

- `Titanic_orange_assign.ows` — Orange workflow file

## How to Run

Open `Titanic_orange_assign.ows` in [Orange 3](https://orangedatamining.com/). Double-click **Test and Score** to view accuracy, AUC, and other metrics, or **ROC Analysis** to view the ROC curve.

## Key Takeaways

- Demonstrates a complete supervised learning pipeline: data cleaning → preprocessing → visualization → modeling → evaluation
- Highlights how visual programming tools like Orange can make ML workflows transparent and easy to iterate on without writing code
