
# HCLTECH Stock Prediction Analysis

This project analyzes and predicts HCLTECH stock prices using time series analysis, particularly ARIMA modeling, to forecast future stock trends based on historical data.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [License](#license)

## Introduction

The project performs stock price prediction for HCLTECH using historical data. Time series decomposition and ARIMA models are applied to explore data trends, seasonality, and to forecast future prices. The project includes data exploration, visualization, and model evaluation metrics to understand stock behavior.

## Dataset

- **Source:** The dataset consists of historical stock data for HCLTECH.
- **Columns:**
  - `Date`: Trading date.
  - `Open`: Opening price on the trading day.
  - `High`: Highest price on the trading day.
  - `Low`: Lowest price on the trading day.
  - `Close`: Closing price on the trading day.
  - `Adj Close`: Adjusted closing price.
  - `Volume`: Total volume of shares traded.

## Project Structure

- **Data Exploration:** Initial analysis and visualization of the stock data to identify trends, seasonality, and patterns.
- **Stationarity Check:** Use of statistical tests to check if the data is stationary, a prerequisite for ARIMA modeling.
- **Modeling:** 
  - ARIMA model setup and training.
  - Model evaluation based on mean squared error (MSE) and root mean square error (RMSE).
- **Prediction:** Forecast future stock prices and plot predicted values against actual data for comparison.

## Installation

To run this project, ensure you have Python installed along with the following libraries:
```bash
pip install numpy pandas matplotlib seaborn statsmodels scikit-learn
```

## Usage

1. **Load the Dataset**: Ensure the stock data CSV (`HCLTECH.csv`) is available in the root directory.
2. **Run the Notebook**: Open `HCLTECH_Stock_Prediction_Analysis.ipynb` and execute cells sequentially.
3. **Modify Parameters**: Adjust model parameters in the ARIMA section as needed to experiment with different configurations.

## Results

- Visualizations of historical stock trends and ARIMA model results.
- Predictions of stock prices with calculated MSE and RMSE metrics to assess model accuracy.

## License

This project is licensed under the MIT License.
