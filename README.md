# Task Scheduling using Machine Learning and Deep Learning algorithms

### Deep Learning Model Comparison for Delay Prediction

This project implements and compares several deep learning models to predict the final delay (`final_delay`) based on two input features: `calculated_input_delay` and `calculated_output_delay`. The models used for comparison include:

- **RNN (Recurrent Neural Network)**
- **LSTM (Long Short-Term Memory)**
- **BiLSTM (Bidirectional LSTM)**
- **GRU (Gated Recurrent Unit)**

## Project Overview

The main objective of this project is to predict the `final_delay` using the input features `calculated_input_delay` and `calculated_output_delay`. The dataset is preprocessed, normalized, and split into training and testing sets before feeding it into the deep learning models.

We evaluate the performance of each model using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
