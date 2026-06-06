# 📈 Forecasting the USD/ZMW Exchange Rate Using ARIMA and LSTM Models

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GIVEN-CHINYAMA/usd-zmw-exchange-rate-forecasting/blob/main/usd_zmw_exchange_rate_forecasting.ipynb)
[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://python.org)
[![Status](https://img.shields.io/badge/Status-Completed-green)](https://github.com/GIVEN-CHINYAMA/usd-zmw-exchange-rate-forecasting)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

**Author:** Given Chinyama &nbsp;|&nbsp; **Institution:** Kwame Nkrumah University &nbsp;|&nbsp; **Date:** May 2026

---

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

## 📊 Model Results

| Model | MAPE | Accuracy |
|-------|------|----------|
| ARIMA(3,1,2) | 20.70% | 79.3% |
| **LSTM** | **3.57%** | **96.4%** |

> 🏆 **LSTM significantly outperformed ARIMA** — achieving 96.4% forecast accuracy vs 79.3% for ARIMA on 2,608 daily observations (2015–2024).

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

```
usd-zmw-exchange-rate-forecasting/
│
├── usd_zmw_exchange_rate_forecasting.ipynb  # Main notebook
├── README.md                                # Project documentation
├── LICENSE                                  # MIT License
└── .gitignore                               # Python gitignore
```

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

- **LSTM dramatically outperformed ARIMA** — MAPE of 3.57% vs 20.70%, a 5× improvement in forecast accuracy
- Both models captured the general upward trend of the USD/ZMW exchange rate
- LSTM performed better at capturing short-term fluctuations due to its ability to learn complex non-linear patterns
- ARIMA was faster to train and easier to interpret, but its linear structure limited accuracy on this volatile series
- The Kwacha has depreciated persistently — from approximately ZMW 6/USD in 2015 to over ZMW 25/USD by 2024

---

## 🚀 How to Run This Project

1. Click the **Open in Colab** badge at the top of this page
2. Run all cells from top to bottom using **Runtime → Run All**
3. All required libraries will be installed automatically

Or run locally:

```bash
git clone https://github.com/GIVEN-CHINYAMA/usd-zmw-exchange-rate-forecasting.git
cd usd-zmw-exchange-rate-forecasting
pip install pandas numpy matplotlib seaborn statsmodels tensorflow scikit-learn yfinance
jupyter notebook usd_zmw_exchange_rate_forecasting.ipynb
```

---

## 👤 Author

**Given Chinyama**
Data Scientist · Kwame Nkrumah University · Lusaka, Zambia

[![GitHub](https://img.shields.io/badge/GitHub-GIVEN--CHINYAMA-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GIVEN-CHINYAMA)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-given--chinyama--data-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/given-chinyama-data)
[![Email](https://img.shields.io/badge/Email-givenchinyama%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:givenchinyama@gmail.com)

---

## 📄 License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.

