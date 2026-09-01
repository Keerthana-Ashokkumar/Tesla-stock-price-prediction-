# 📈 Tesla Stock Price Prediction

## 📌 Project Overview

This project focuses on predicting Tesla (TSLA) stock closing prices using Deep Learning time-series models. The complete workflow covers data collection, preprocessing, model building using SimpleRNN and LSTM, hyperparameter tuning, multi-day forecasting, model evaluation, and news sentiment analysis.

---

## 🎯 Objectives

- Collect and preprocess historical Tesla stock price data.
- Build time-series forecasting models using SimpleRNN and LSTM.
- Perform multi-day forecasting (1-day, 5-day, and 10-day ahead closing prices).
- Tune hyperparameters to improve model performance.
- Evaluate models using standard regression metrics.
- Incorporate news sentiment analysis to study its impact on stock price movement.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- TensorFlow / Keras
- SimpleRNN, LSTM
- Matplotlib, Seaborn
- Scikit-learn

---

## 📂 Dataset

Source: **Historical Tesla (TSLA) stock price data**

Key Features:
- Date
- Open, High, Low, Close prices
- Volume

---

## 🔄 Project Workflow

1. Data collection and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature scaling and sequence preparation
4. Model building (SimpleRNN and LSTM)
5. Hyperparameter tuning
6. Multi-day forecasting (1-day, 5-day, 10-day)
7. Model evaluation
8. News sentiment analysis

---

## 🧠 Modeling Approach

### 🔹 SimpleRNN Model
- Baseline recurrent model for sequential stock price data.

### 🔹 LSTM Model
- Captures long-term dependencies in stock price trends, giving improved forecasting performance over SimpleRNN.

### 🔹 Multi-Day Forecasting
- Models trained to predict closing price 1 day, 5 days, and 10 days ahead.

### 🔹 Hyperparameter Tuning
Tested multiple combinations of:
- Number of layers and units
- Learning rate
- Batch size
- Epochs
- Dropout rate

---

## 📊 Model Evaluation

Metrics used to evaluate model performance:
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

---

## 📰 News Sentiment Analysis

- Collected Tesla-related news headlines.
- Performed sentiment scoring to understand correlation between news sentiment and stock price movement.

---

## 📈 Key Insights

- LSTM outperformed SimpleRNN in capturing long-term price trends.
- Forecast accuracy decreases as the prediction horizon increases (1-day > 5-day > 10-day).
- News sentiment shows a noticeable correlation with short-term price fluctuations.

---

## 🚀 Results

- Built and compared SimpleRNN and LSTM models for stock price forecasting.
- Achieved multi-day (1/5/10-day) closing price predictions.
- Evaluated models comprehensively using MSE, RMSE, MAE, and R² Score.
- Analyzed the impact of news sentiment on Tesla stock price movement.

---

## 📌 Future Enhancements

- Incorporate additional technical indicators (RSI, MACD, Moving Averages).
- Real-time stock data API integration.
- Deploy as an interactive Streamlit web application.
- Experiment with Transformer-based time-series models.

---

## 🧰 Technology Stack

| Category | Tools |
|---|---|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Deep Learning | TensorFlow, Keras (SimpleRNN, LSTM) |
| Evaluation | Scikit-learn |

---

## 📦 Project Deliverables

- Data preprocessing notebook
- SimpleRNN and LSTM model notebooks
- Hyperparameter tuning notebook
- Multi-day forecasting results
- Model evaluation report (MSE, RMSE, MAE, R² Score)
- News sentiment analysis notebook
- Project documentation
