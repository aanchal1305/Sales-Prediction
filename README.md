# Sales-Prediction
Sales prediction is used to understand and analyze different factors to help increase sales by applying a basic neural network model.

## Project Overview
This project implements an Artificial Neural Network (ANN) to forecast product sales based on customer data including demographic information and financial metrics.

## Methodology
1. Data Preprocessing
   (a) Handle missing values through removal
   (b) Encode categorical variables (country)
   (c) Feature engineering (debt-to-salary ratio, net-worth-to-salary)
   (d) Outlier detection and removal using IQR method
   (e) Feature scaling using StandardScaler

2. Model Architecture
   (a) Input layer: 8 features
   (b) Hidden layers: 3 dense layers (64, 32, 16 neurons) with ReLU activation
   (c) Dropout layers (0.2) for regularization
   (d) Output layer: 1 neuron for regression
   (e) Optimizer: Adam
   (f) Loss: Mean Squared Error

3. Evaluation
   (a) Metrics: MSE, R2 Score
   (b) Visualizations: Training history, Predicted vs Actual plot

(*) The code includes:
- Data preprocessing with missing value handling and outlier detection
- Feature engineering to capture financial relationships
- ANN model with dropout for regularization
- Model evaluation with appropriate metrics
- Visualization of results
- Model saving for future use

(*) The resulting model can help businesses:
- Predict car purchase amounts based on customer characteristics
- Identify which factors most influence purchasing behavior
- Optimize marketing strategies by focusing on high-value customer segments
