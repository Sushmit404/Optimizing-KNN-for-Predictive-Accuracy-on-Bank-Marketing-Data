# Optimizing KNN for Predictive Accuracy on Bank Marketing Data

## Overview
This project implements and optimizes a **K-Nearest Neighbors (KNN)** model to predict whether a customer will subscribe to a bank’s term deposit using the **Bank Marketing Dataset**.

## Key Steps:
- **Data Preprocessing**: Converted categorical data into numerical form using `Pandas` and performed an 80-20 train-test split.
- **KNN Implementation**: Built a KNN model to predict customer subscriptions, achieving up to **89% accuracy**.
- **Model Enhancement**: Improved accuracy to **90.5%** by applying **StandardScaler** for feature normalization.

## Technologies Used:
- **Pandas** for data handling
- **Scikit-learn** for model building and scaling
- **StandardScaler** for data normalization

## Usage:
1. Clone the repository and install dependencies.
2. Download the dataset or connect to it via the provided API.
3. Run the `KNN` model using different numbers of neighbors and analyze accuracy.
4. Apply cross-validation and scaling for improved results.
