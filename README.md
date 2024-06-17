# Shallow Neural Network

## Overview

In this project, we'll build a shallow neural network from scratch and train it on the Pima Indians Diabetes dataset.

## Dataset

We'll use the Pima Indians Diabetes dataset, which includes data on 768 Native American women to study type 2 diabetes risk factors.

## Steps

1. **Read the Dataset**: Load training data from `diabetes_train.csv` and test data from `diabetes_test.csv`.
2. **Preprocess**: Separate the target variable (`Outcome`), normalize features, convert to NumPy arrays, and split into training and validation sets.
3. **Modeling**:
   - Create a `Model` class with `__init__`, `predict`, `update_weights_for_one_epoch`, and `fit` functions.
   - Initialize weights with mean `0` and std `0.01`.
   - Implement forward and backward propagation.
4. **Training**: Instantiate the model, call `fit`, and experiment with different learning rates and epochs.
5. **Prediction**: Compute outputs for test data and predict `True` if output > `0.5`, else `False`.
