# K-Nearest Neighbors on USPS Dataset

## Overview

This project implements and evaluates a K-Nearest Neighbors (KNN) classifier on the USPS dataset. The notebook covers the following steps:

1. Import necessary libraries
2. Load the USPS dataset
3. Visualize some training images
4. Train and evaluate the KNN model with different values of K

## Steps

### 1. Import Libraries

Essential libraries are imported for handling the dataset, creating visualizations, and implementing machine learning models.

### 2. Load the USPS Dataset

The dataset is loaded from an HDF5 file, extracting training and testing data along with their labels.

### 3. Visualize Training Images

The first 10 training images are visualized in a single row with their corresponding labels.

### 4. Train and Evaluate the KNN Model

The KNN model is trained with different values of K (number of neighbors) and evaluated using cross-validation and test set metrics. Metrics such as accuracy, confusion matrix, precision, recall, and F1 score are computed.

## Results

The notebook provides results for different values of K, showing accuracy for each fold in cross-validation, average accuracy, test accuracy, confusion matrix, and precision/recall scores.
