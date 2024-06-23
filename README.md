# Bank Customer Churn Prediction Using ANN

![License](https://img.shields.io/github/license/yourusername/Bank-Customer-Churn-Prediction-ANN)
![Issues](https://img.shields.io/github/issues/yourusername/Bank-Customer-Churn-Prediction-ANN)
![Stars](https://img.shields.io/github/stars/yourusername/Bank-Customer-Churn-Prediction-ANN)
![Forks](https://img.shields.io/github/forks/yourusername/Bank-Customer-Churn-Prediction-ANN)

## Project Overview

This project utilizes an Artificial Neural Network (ANN) to predict whether bank customers will stay with the bank or leave (churn). The model is trained on a dataset of 10,000 customers, using various features such as demographic information, account details, and behavioral data.

## Dataset

The dataset comprises information on 10,000 bank customers, including the following features:

- **CustomerID**: Unique identifier for each customer
- **Geography**: Country of residence (France, Germany, Spain)
- **Gender**: Male or Female
- **Age**: Age of the customer
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance
- **NumOfProducts**: Number of bank products the customer is using
- **HasCrCard**: Indicates if the customer has a credit card (0 or 1)
- **IsActiveMember**: Indicates if the customer is an active member (0 or 1)
- **EstimatedSalary**: Annual salary of the customer
- **Exited**: Indicates if the customer has churned (1) or not (0)

## Model

The ANN model is built using Keras and TensorFlow, featuring the following architecture:

- **Input Layer**: Takes in the features of the dataset
- **Dense Layer**: Fully connected layer with ReLU activation
- **Dense Layer**: Fully connected layer with ReLU activation
- **Output Layer**: Fully connected layer with Sigmoid activation for binary classification

## Results

The model achieves a satisfactory accuracy on the test set. Below is the confusion matrix representing the performance of the model:

[[1578   17]
 [ 316   89]]
0.8335
