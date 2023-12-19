# Stock Price Prediction using LSTM
This repository contains a Python stock price prediction model implementation using Long Short-Term Memory (LSTM) networks. The model is designed to predict the future stock prices of IBM based on historical data.

## Overview
The code is structured as follows:

**Data Loading and Visualization:** The historical stock data for IBM is loaded using the Pandas library, and a visual representation of the training and test sets is plotted using Matplotlib.

**Data Preprocessing:** The data is preprocessed, including scaling using Min-Max scaling, and then separated into training and test sets.

**LSTM Model:** The core of the predictive model is built using a Sequential model in Keras. It consists of multiple LSTM layers with Dropout regularization to prevent overfitting.

**Training:** The model is trained on the training set using the Adam optimizer and Mean Squared Error loss.

**Prediction:** The trained model predicts future stock prices on the test set.

**Visualization:** The results are visualized by plotting the real IBM stock prices against the predicted prices.

## Requirements
Python 3

**Libraries:** Pandas, Matplotlib, NumPy, Scikit-learn, Keras
## Usage
Clone the repository.
Please ensure the required libraries are installed (pip install -r requirements.txt).
Run the provided Python script.
Feel free to experiment with the code, modify parameters, and enhance the model for your needs.
