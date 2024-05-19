# Cancer Detection using Logistic Regression

This repository contains a Jupyter Notebook that implements a binary classification algorithm on a cancer dataset to differentiate between benign and malignant tumors using logistic regression with polynomial features.

## Overview

The notebook covers the following steps:

1. **Data Loading**: Load the cancer dataset from a CSV file.
2. **Data Preprocessing**: Clean and preprocess the dataset by removing unnecessary columns and mapping categorical values to integers.
3. **Data Splitting**: Split the data into training and test sets.
4. **Feature Transformation**: Implement polynomial features and min-max normalization.
5. **Model Implementation**: Implement logistic regression with gradient descent, including functions for sigmoid activation, loss calculation, and predictions.
6. **Model Training**: Train the logistic regression model on the training set.
7. **Model Evaluation**: Evaluate the model using confusion matrix, precision, recall, F1 score, and accuracy.
8. **Learning Curve**: Plot the learning curve to visualize the loss over epochs.

## Dependencies

The project requires the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn

You can install the required libraries using `pip`:

```bash
pip install numpy pandas matplotlib seaborn
