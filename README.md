📈 Forecasting the USD/ZMW Exchange Rate Using ARIMA and LSTM Models

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Completed-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Project Overview

This project forecasts the USD/ZMW (US Dollar to Zambian Kwacha) exchange rate
using two time series forecasting models — ARIMA (a classical statistical model)
and LSTM (a deep learning model). The goal is to compare both approaches and
determine which one better captures the trends and patterns in the exchange rate data.

---

## 🎯 Objectives

- Collect and preprocess historical USD/ZMW exchange rate data
- Perform Exploratory Data Analysis (EDA) to understand trends and patterns
- Build and evaluate an ARIMA model for time series forecasting
- Build and evaluate an LSTM (Long Short-Term Memory) neural network model
- Compare the performance of both models using error metrics
- Visualize forecast results against actual exchange rate values

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Google Colab | Development environment |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib / Seaborn | Data visualization |
| Statsmodels | ARIMA model |
| TensorFlow / Keras | LSTM model |
| Scikit-learn | Data preprocessing & evaluation |

---

## 📂 Project Structure
usd-zmw-exchange-rate-forecasting/
│
├── usd_zmw_exchange_rate_forecasting.ipynb  # Main notebook
├── README.md                                 # Project documentation
├── LICENSE                                   # MIT License
└── .gitignore                                # Python gitignore

---

## 📊 Models Used

### 1. ARIMA (AutoRegressive Integrated Moving Average)
- A classical statistical model for time series forecasting
- Captures linear trends and seasonality in the data
- Parameters selected using ACF and PACF plots

### 2. LSTM (Long Short-Term Memory)
- A type of Recurrent Neural Network (RNN) designed for sequential data
- Capable of learning long-term dependencies in time series
- Built using TensorFlow/Keras

---

## 📉 Model Evaluation Metrics

Models were evaluated using the following metrics:

- **MAE** — Mean Absolute Error
- **RMSE** — Root Mean Squared Error
- **MAPE** — Mean Absolute Percentage Error

---

## 🔍 Key Findings

- Both ARIMA and LSTM were able to capture the general upward trend of the
  USD/ZMW exchange rate
- LSTM performed better at capturing short-term fluctuations due to its
  ability to learn complex patterns
- ARIMA was faster to train and easier to interpret for shorter forecast horizons

---

## 🚀 How to Run This Project

1. Click the **"Open in Colab"** button at the top of the notebook
2. Run all cells from top to bottom using **Runtime → Run All**
3. All required libraries will be installed automatically

---

## 👤 Author

**Given Chinyama**
Kwame Nkrumah University
May 2026

---

## 📄 License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
