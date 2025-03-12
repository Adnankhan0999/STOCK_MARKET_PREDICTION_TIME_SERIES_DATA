Stock Analysis and Prediction App

This repository contains a Streamlit application designed for stock analysis and prediction. It includes features such as stock information, stock price prediction using ARIMA models, CAPM return and beta calculations, and detailed stock analysis with technical indicators.

Features
Stock Information: Provides an overview of a stock, including its business summary, sector, and key financial metrics.

Stock Prediction: Predicts the closing prices for the next 30 days using historical data and ARIMA models.

Stock Analysis: Offers detailed analysis with historical data visualization, RSI, MACD, and moving averages.

Requirements
To run this application, you need to install the following packages:
pip install streamlit pandas yfinance plotly pandas_ta numpy scikit-learn statsmodels

Files
Trading_App.py: The main application file that sets up the trading guide app.

Stock_Prediction.py: Contains the stock prediction functionality using ARIMA models.

Stock_Analysis.py: Provides detailed stock analysis with various technical indicators.

model_train.py: Includes functions for training and evaluating stock price prediction models.

plotly_figure.py: Contains functions for creating Plotly figures used in the app.

How to Run

Clone the repository:

bash

git clone https://github.com/Adnankhan0999/stock-analysis-app.git

Navigate to the repository directory:

bash

cd stock-analysis-app

Install the required packages:

bash

pip install -r requirements.txt

If you don't have a requirements.txt file, you can create one with the necessary packages or install them manually as mentioned in the Requirements section.

Run the application:

bash

streamlit run Trading_App.py

This will start the Streamlit server and open the app in your default web browser.


