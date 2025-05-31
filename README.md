# Currency Prediction using LSTM model


## Overview

This project implements a Long Short-Term Memory (LSTM) neural network model to predict currency exchange rates based on historical data. The model uses time-series forecasting techniques to learn from past currency values and forecast future rates with high accuracy.

---

## Dataset

- The dataset contains historical currency exchange rates with columns:
  - **NO**: Serial number
  - **Tanggal**: Date (YYYY-MM-DD)
  - **Rate**: Currency exchange rate (target variable)

---

## Features

- Data preprocessing including:
  - Checking for missing values and outliers
  - Normalizing data with `MinMaxScaler`
- Creating time step sequences for LSTM input
- Splitting data into training and testing sets (80/20)
- Building and training an LSTM model
- Model evaluation with:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Percentage Error (MAPE)
- Visualizing actual vs predicted currency rates

---

## Installation

Make sure you have Python 3.x installed along with these packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
