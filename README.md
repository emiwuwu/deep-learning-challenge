# Alphabet Soup Deep Learning Model

## Overview

The Alphabet Soup Deep Learning Model project aims to predict the success of charitable organizations funded by Alphabet Soup, a nonprofit organization. The project's purpose is to improve the allocation of funds to ensure that they are used effectively, thereby increasing the impact of donations.


## Project Description

- This project leverages deep learning and neural network techniques to construct a robust classification model.
- The primary objective is to forecast the effective utilization of funds allocated to charitable organizations.
- The project entails vital elements including data preprocessing, model compilation, feature engineering, and hyperparameter tuning to optimize predictive performance.

## Data Preprocessing

- Data includes features such as "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," and others.
- The target variable is "IS_SUCCESSFUL," indicating successful (1) or unsuccessful (0) funding.
- Unnecessary variables like "EIN" have been removed to streamline the dataset.

## Model Architecture

**AlphabetSoupCharity.h5:**

- A deep neural network model, denoted as `AlphabetSoupCharity.h5`, is utilized.
- It includes an input layer, two hidden layers, and an output layer.
- The activation function employed in the hidden layers is `sigmoid`.
- `AlphabetSoupCharity.h5` is designed to capture the underlying patterns within the data.

**AlphabetSoupCharity_Optimization.h5:**

- A deep neural network model, represented as `AlphabetSoupCharity_Optimization.h5`, is employed.
- This model features an input layer, three hidden layers, and an output layer.
- The activation function chosen for the hidden layers is `ReLU` (Rectified Linear Unit).
- The primary objective of `AlphabetSoupCharity_Optimization.h5` is to capture and model the complex relationships present in the dataset.

## Hyperparameter Tuning

- Keras Tuner is employed to optimize hyperparameters such as the number of neurons, layers, activation functions, and learning rate.
- Multiple trials are run to find the best combination of hyperparameters.

## Training and Evaluation

- Early stopping with a patience of 3 is implemented to avoid overfitting and achieve better model generalization.
- Model performance is evaluated based on accuracy.

## Results

- The target model performance was set to attain a classification accuracy of 75% for distinguishing between successful and unsuccessful funding allocation.
- Model enhancements were introduced through a combination of hyperparameter tuning, early stopping, and feature engineering.
- The initial model `AlphabetSoupCharity.h5` fell short of expectations, while the improved model `AlphabetSoupCharity_Optimization.h5` succeeded in achieving the desired accuracy threshold.

## Usage

- The model can be used to predict the success of charitable organizations' funding allocation.
- It can be incorporated into applications or workflows that require such predictions.

## Analysis Report

- For a comprehensive analysis of deep learning models, please refer to the [Alphabet Soup Deep Learning Model Analysis Report](Deep_Learning_Challenge/Analysis_Report.md)
