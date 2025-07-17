# 📈 Stock Price Prediction Using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict Google's stock opening prices based on historical data. It applies time series forecasting techniques and deep learning to model complex temporal dependencies in financial data.

---

## 🚀 Project Overview

- **Goal**: Predict future stock opening prices using past market data
- **Model**: LSTM (Recurrent Neural Network)
- **Framework**: TensorFlow / Keras
- **Data**: Google's historical stock data (CSV)

---

## 📂 Dataset

The dataset used is `google_stock_price_full.csv` and includes:
- `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`

### 🕒 Time-Based Splits
- **Training set**: Until June 30, 2023  
- **Validation set**: July 1, 2023 – Dec 31, 2023  
- **Test set**: Jan 1, 2024 – Feb 29, 2024

---

## 🛠️ Features & Tools

- Time series preprocessing (windowing, normalization)
- LSTM network with:
  - Multiple layers
  - Dropout for regularization
  - Dense output layer
- Evaluation with validation loss and prediction visualization
- Checkpointing best model with `ModelCheckpoint`

---

## 📊 Model Performance

- Validation Loss: ~0.0012 (MSE)
- Consistent training curve, improving validation accuracy over time
- Visual plots to compare training vs. validation loss and forecasted vs. actual prices

---

## 🖼️ Sample Plots

- 📉 Open & Close price over time
- 🟠 Training vs. Validation loss (125 epochs)
- 🔵 Forecasted vs. Actual Open Prices on Test Data

---
