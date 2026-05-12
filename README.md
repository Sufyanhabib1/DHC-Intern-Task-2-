# DHC-Intern-Task-2

# Stock Price Prediction using Machine Learning

This project predicts the next day's stock closing price using historical stock market data fetched from Yahoo Finance with the `yfinance` library.

The project uses Machine Learning regression models such as:
- Linear Regression
- Random Forest Regressor

## Features
- Fetch real time historical stock data
- Data preprocessing for time series prediction
- Feature selection using Open, High, Low, and Volume
- Predict next day closing prices
- Visualize actual vs predicted stock prices
- Model evaluation using MAE and MSE

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit learn
- yfinance

## Dataset
Stock market data is retrieved directly from Yahoo Finance using the `yfinance` API.

Example stock used:
 Tesla (TSLA)

## Machine Learning Workflow
1. Load stock data
2. Preprocess dataset
3. Create target column for next day prediction
4. Train regression model
5. Evaluate model performance
6. Plot actual vs predicted prices

## Installation

Install required libraries:

```bash
pip install yfinance pandas numpy matplotlib scikit learn
