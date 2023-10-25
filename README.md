# Data Mining Cup 2019 - Fraud Detection

This project focuses on fraud detection in retail transactions using the Data Mining Cup 2019 dataset. It includes data analysis, preprocessing, feature engineering, and the evaluation of various machine learning models.

## Overview

- `data` folder contains the training and testing data in CSV format.
- `DMC-2019-realclass.csv` contains the real class labels for testing data.
- `train.csv` is the main dataset used for training the models.

## Data Analysis

- Class distribution: This dataset has a severe class imbalance with fraudulent transactions forming a minority.
- Feature distribution: Investigate the distribution of features like trustLevel, totalScanTimeInSeconds, grandTotal, lineItemVoids, etc.
- Correlation analysis: Explore the correlation between features and the target variable (fraud).

## Preprocessing

- Data cleaning: Handle missing values and inconsistencies in the data.
- Feature engineering: Create new features like TotalItemsScanned and various ratios.
- Downsampling: Address class imbalance by downsampling the majority class.

## Model Evaluation

- Several machine learning models, including Logistic Regression, Random Forest, Decision Tree, K-Nearest Neighbors, and Gradient Boosting, are trained and evaluated.
- Evaluation metrics include precision, recall, F1-score, ROC AUC, and visualizations.

## Model Prediction

- The best model is selected and used to make predictions on the test data.
- Real class labels are compared to predicted labels to assess model performance.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/zaza-ipynb/Data-Mining-Cup-2019.git

