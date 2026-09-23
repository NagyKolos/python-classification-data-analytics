# python-classification-data-analytics

Python and scikit-learn classification project comparing statistical and machine learning models for personal loan prediction.

## Project Overview

This project uses Python and scikit-learn to compare classification models for predicting whether a bank customer accepts a personal loan offer.

The analysis focuses on preparing customer data, developing multiple classification models, optimizing a Neural Network, and evaluating model performance.

## Objectives

- Prepare customer data for classification
- Compare different classification algorithms
- Optimize the Neural Network using 5-fold GridSearchCV
- Evaluate model performance using training and validation accuracy
- Analyze confusion matrices and model performance

## Dataset

The project uses the Universal Bank dataset.

The target variable is **Personal Loan**, which indicates whether a customer accepted a personal loan offer.

The analysis includes customer characteristics used as predictors, with categorical variables prepared for use in the classification models.

## Models

Three classification approaches were evaluated:

- Linear Discriminant Analysis
- Logistic Regression
- Neural Network

## Model Optimization

The Neural Network was optimized using **GridSearchCV with 5-fold cross-validation**.

Different neural network configurations were evaluated to identify an optimized model.

## Results

The optimized Neural Network achieved **95.75% validation accuracy** in the analysis.

Model performance was evaluated using:

- Training accuracy
- Validation accuracy
- Confusion matrices
- Cross-validation during model optimization

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- scikit-learn
- GridSearchCV
- Classification Modeling
- Cross-Validation
- Model Evaluation

## Skills Demonstrated

- Data preparation
- Classification modeling
- Machine learning
- Feature preparation
- Model comparison
- Hyperparameter optimization
- Cross-validation
- Model performance evaluation

## Project Notebook

[Open the Jupyter Notebook](python_classification_analysis_clean.ipynb)
