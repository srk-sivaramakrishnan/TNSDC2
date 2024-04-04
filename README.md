##Stock Price Prediction with MLPRegressor and Prophet

#Overview
This repository contains code for predicting stock prices using two different approaches: MLPRegressor from scikit-learn and Prophet by Facebook. The MLPRegressor model is implemented using neural networks, while Prophet is a forecasting tool specifically designed for time series data.

#Data
The dataset used for this project is AAPL.csv, which contains historical stock prices of Apple Inc. The dataset consists of the following columns:

Date: The date of the stock price data
Open: The opening price of the stock
High: The highest price of the stock during the day
Low: The lowest price of the stock during the day
Close: The closing price of the stock
Volume: The volume of stocks traded on that day
Setup
To run the code, follow these steps:

Clone this repository to your local machine.
Ensure you have the required dependencies installed, such as pandas, numpy, scikit-learn, seaborn, Prophet, and plotly.
Run the provided Jupyter Notebook or Python script to execute the code.
Results
The MLPRegressor model achieved an R2 score of approximately 0.9997 on the test dataset, indicating a high level of accuracy in predicting stock prices. Additionally, Prophet was used to forecast future stock prices, providing insights into potential trends.

Files
AAPL.csv: The dataset containing historical stock prices of Apple Inc.
MLPRegressor_Stock_Price_Prediction.ipynb: Jupyter Notebook containing code for training and evaluating the MLPRegressor model.
Prophet_Stock_Price_Prediction.ipynb: Jupyter Notebook containing code for training and evaluating the Prophet model.
README.md: This file providing an overview of the project and instructions for running the code.

Conclusion
Both the MLPRegressor and Prophet models demonstrated promising results in predicting stock prices. These models can be further optimized and fine-tuned to improve performance and provide more accurate forecasts.
