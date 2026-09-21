# Diabetes Progression Prediction using ANN

## Project Overview

This project uses an **Artificial Neural Network (ANN)** to predict diabetes disease progression using the Diabetes dataset available in `scikit-learn`.

The project covers data preprocessing, exploratory data analysis, feature normalization, ANN model development, evaluation, and model improvement.

##  Objective

To develop a deep learning regression model that predicts diabetes progression based on patient-related independent variables.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

##  Project Workflow

1. Load the Diabetes dataset from Scikit-learn
2. Check and handle missing values
3. Perform Exploratory Data Analysis
4. Visualize feature and target relationships
5. Split data into training and testing sets
6. Normalize the input features
7. Build and train a basic ANN
8. Evaluate the model using MAE, MSE, and R²
9. Improve the ANN architecture
10. Compare the original and improved models

## Model Architecture

### Original ANN

* Input layer: 10 features
* Hidden layers with ReLU activation
* Output layer: 1 neuron for regression

### Improved ANN

* Increased number of neurons
* Additional hidden layers
* Dropout regularization
* Early stopping
* Adam optimizer

## Model Performance

| Model        |   MAE |     MSE | R² Score |
| ------------ | ----: | ------: | -------: |
| Original ANN | 51.82 | 4335.92 |   0.1816 |
| Improved ANN | 43.21 | 2893.35 |   0.4539 |

## Improvement

The improved ANN achieved:

* Lower **MAE**: 51.82 → 43.21
* Lower **MSE**: 4335.92 → 2893.35
* Higher **R² Score**: 0.1816 → 0.4539

This shows that the improved architecture performed better than the original ANN on the test dataset.

## Dataset

The project uses the built-in **Diabetes dataset** from `sklearn.datasets`.

It contains:

* 442 samples
* 10 input features
* 1 target variable representing diabetes disease progression

## Conclusion

An ANN regression model was developed to predict diabetes progression. After improving the network architecture and training strategy, the model achieved better test performance, with an R² score of **0.4539**.

This project demonstrates the application of deep learning techniques to a healthcare-related regression problem.

