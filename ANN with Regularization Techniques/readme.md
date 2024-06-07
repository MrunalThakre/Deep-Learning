# Diabetes Prediction Using Artificial Neural Networks

This project aims to predict diabetes using an Artificial Neural Network (ANN) with various regularization techniques and hyperparameter tuning.

## Table of Contents
- [Data Preparation and EDA](#data-preparation-and-eda)
- [Data Preprocessing](#data-preprocessing)
- [Model Design and Training](#model-design-and-training)
- [Model Evaluation](#model-evaluation)
- [Regularization Techniques](#regularization-techniques)
- [Experimentation](#experimentation)
- [Comparative Analysis](#comparative-analysis)
- [Requirements](#requirements)
- [How to Run](#how-to-run)

## Data Preparation and EDA
- Load and visualize the dataset.
- Check for missing values and visualize relationships using pair plots and correlation matrix.

## Data Preprocessing
- Scale features using StandardScaler.
- Split the dataset into training and testing sets.

## Model Design and Training
- Define a Sequential model with Dense layers.
- Compile the model using the Adam optimizer.
- Train the model with early stopping.

## Model Evaluation
- Evaluate the model on the test set.
- Generate classification report and confusion matrix.
- Plot training history for loss and accuracy.

## Regularization Techniques
- Apply L1, L2 regularization, and dropout to prevent overfitting.

## Experimentation
- Experiment with different numbers of epochs, learning rates, and batch sizes.
- Evaluate and compare the performance of various hyperparameter settings.

## Comparative Analysis
- Summarize and compare the performance of different models and settings.

## Requirements
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- tensorflow

## How to Run
1. Clone the repository.
2. Install the required packages.
3. Run the script to train and evaluate the model.

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
python diabetes_prediction.py
