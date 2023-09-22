# Stock_Price_PREDICTION
Stock Price Prediction using LSTM model 

![stock](https://github.com/Navneet-kaur-19/Stock_Price_PREDICTION/assets/140330208/43ef61eb-39c1-4eca-bda9-30b21f1e9abd)







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

Results

Contributing

License







Getting Started



1.I used Jupyter Notebook 

    

3.Download Dataset : 

  Two ways: 
    - Download Historical Data from online Source ,i.e , yahoofinance website
    <img width="1728" alt="Screenshot 2023-09-22 at 20 55 09" src="https://github.com/Navneet-kaur-19/Stock_Price_PREDICTION/assets/140330208/d88b4f9c-47dd-42f1-b828-91b59048e22f">




    - Can use yahoo finance API 
      bash
      pip install yfinance
<img width="1728" alt="Screenshot 2023-09-22 at 20 58 32" src="https://github.com/Navneet-kaur-19/Stock_Price_PREDICTION/assets/140330208/096ce273-8afe-46b2-a430-1ce2783206ab">

    

 

Dataset




I use AAPL dataset for training and evaluation model.You can use any Stock price data
.This dataset contains historical stock price data for AAPL and includes features such as date, open price, close price, volume, etc.








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


<img width="1728" alt="Screenshot 2023-09-22 at 21 00 45" src="https://github.com/Navneet-kaur-19/Stock_Price_PREDICTION/assets/140330208/00725d86-3f28-4f42-bf70-67f0baf03238">









Contributing





We welcome contributions from the community. If you have any suggestions, bug reports, or feature requests, please create an issue or submit a pull request.




License




This project is licensed under the MIT License.




