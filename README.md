# Stock_Price_PREDICTION
Stock Price Prediction using LSTM model 

Overview
This repository contains code and resources for building a stock price prediction model using an LSTM neural network. The LSTM model is a type of recurrent neural network (RNN) that is particularly well-suited for time series forecasting tasks, such as predicting stock prices.

Table of Contents
Overview
Getting Started
Dataset
Requirements
Model Architecture
Training
Evaluation
Usage
Results
Contributing
License

Getting Started

1.I used Jupyter Notebook 
2.Install Required packages:

bash
pip install -r requirements.txt

3.Download Dataset : 
  Two ways: 
    - Download Historical Data from online Source ,i.e , yahoofinance website
    - Can use yahoo finance API 
      bash
      pip install yfinance


Dataset

We use AAPL dataset for training and evaluation model.This dataset contains historical stock price data for AAPL and includes features such as date, open price, close price, volume, etc.


Requirements
Python 3
TensorFlow 2.x
NumPy
Pandas
Matplotlib
Datetime
Sklearn
Keras


Model Architecture


Our stock price prediction model is based on an LSTM neural network architecture. The LSTM layers allow the model to capture temporal dependencies in the stock price data, making it well-suited for time series forecasting.

![lstm](https://github.com/Navneet-kaur-19/Stock_Price_PREDICTION/assets/140330208/911f6545-3ac9-4486-b0ee-ae233bc4e2c7)

Training 

I divided Dataet into 70% and 30% as Training dataset and Testing dataset 
The model is trained on 70% data that is stored in X_train and Y_train Variable 

Evaluation

I evaluate the model's performance using various metrics, including Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). 

Results

I have achieved promising results in predicting stock prices using our LSTM model. The evaluation metrics demonstrate the model's accuracy and its ability to capture stock price trends.

Contributing
We welcome contributions from the community. If you have any suggestions, bug reports, or feature requests, please create an issue or submit a pull request.

License
This project is licensed under the MIT License.
