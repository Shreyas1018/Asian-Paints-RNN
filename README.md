# Asian Paints Stock Prediction using RNN
This project aims to develop a model using Recurrent Neural Networks (RNNs) with Gated Recurrent Units (GRUs) to forecast future stock prices for Asian Paints.

# Data:

The model will be trained on time-series data of Asian Paints stock prices. This data will includes historical closing prices, volumes, and potentially other relevant financial indicators.<br>
Dataset can be found [here](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data)<br>
# Model:

A GRU-based RNN will be implemented. RNNs are well-suited for sequential data like time series, as they can learn from past information to make predictions. GRUs address a limitation of standard RNNs by using gates to control the flow of information, improving their ability to capture long-term dependencies.
# Model Development:

Define the GRU-based RNN architecture, specifying the number of hidden layers, neurons, and other hyperparameters.
Train the model on the prepared time-series data.
Evaluating the model's performance using metrics like Mean Squared Error (MSE).
# Prediction:

Use the trained model to predict future closing prices for Asian Paints stock.
# Project Deliverables:

- A trained GRU-RNN model for predicting Asian Paints stock prices.
- Evaluation results demonstrating the model's performance.
- Visualization of predicted prices compared to actual prices.
