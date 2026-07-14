# Customer Churn Prediction Using Artificial Neural Network

This project explores customer churn prediction using a deep learning approach built with TensorFlow and Keras. The notebook trains an Artificial Neural Network (ANN) to classify whether a customer is likely to leave a service provider, based on historical customer data.

## Overview

Customer churn is a critical business problem because retaining existing customers is often more cost-effective than acquiring new ones. In this project, we use a telecom customer dataset to build and evaluate a neural network model that predicts churn behavior.

The workflow includes:
- loading and exploring the dataset
- cleaning and preprocessing categorical and numerical features
- handling class imbalance with appropriate sampling strategies
- training an ANN model
- evaluating model performance using accuracy, loss, and confusion matrix insights

## Project Files

- Customer-churn-using ANN.ipynb — main Jupyter notebook containing the full workflow
- WA_Fn-UseC_-Telco-Customer-Churn.csv — telecom customer dataset used for training and evaluation
- README.md — project overview and usage guide

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow / Keras
- Scikit-learn

## Dataset

The project uses the Telco Customer Churn dataset, which contains customer information such as:
- tenure
- monthly charges
- contract type
- payment method
- service subscriptions
- churn label

## Workflow

1. Import and inspect the dataset.
2. Perform data cleaning and feature engineering.
3. Convert categorical values into model-friendly formats.
4. Split the data into training and testing sets.
5. Train an ANN model to predict churn.
6. Measure the model’s performance and review key evaluation metrics.

## Model Summary

The notebook builds a neural network classifier for binary prediction:
- input layer based on the processed feature set
- hidden layers with activation functions
- output layer using sigmoid activation for binary classification

The notebook demonstrates that the ANN can learn important patterns in the dataset and produce meaningful churn predictions.

## Requirements

To run the notebook locally, install the required packages:

```bash
pip install pandas numpy matplotlib seaborn tensorflow scikit-learn jupyter
```

## How to Run

1. Open the notebook in Jupyter Notebook or VS Code with the Python extension.
2. Make sure the dataset file is in the same directory as the notebook.
3. Run the cells in order.

## Notes

This project is a practical example of applying deep learning to a real-world classification problem. It is useful for learning how to:
- preprocess tabular data for neural networks
- work with imbalanced datasets
- train and evaluate ANN models
- interpret churn-related business insights

## Result

The notebook shows that the ANN model performs reasonably well on this churn prediction task, with accuracy in the high 80% range during evaluation.
