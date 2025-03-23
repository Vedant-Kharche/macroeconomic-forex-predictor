# PROJECT OVERVIEW 
This project applies Deep Learning models — specifically Long Short-Term Memory (LSTM) networks, Transformer models, and Support Vector Regression (SVR) — to predict the Kenya Shilling (KES) vs US Dollar (USD) foreign exchange rate. The models are trained using macroeconomic indicators including inflation, interest rates, GDP, trade balance, and more.
Our aim is to analyze, compare, and evaluate the predictive capabilities of LSTM and Transformer models in financial time series forecasting using real-world economic data.

## DATASET 
Source: Central Bank of Kenya (CBK)
Period: 2004–2024 (Daily observations)
Features:
Annual Average Inflation
12-Month Inflation
Interest Rates
GDP
Trade Balance (Imports - Exports)
Target: Forex Mean Price (KES/USD)

## MODELS 
Support Vector Regression (SVR)
Long Short-Term Memory (LSTM)
Transformer (Self-Attention-Based)

## KEY FINDINGS 

LSTM outperformed SVR and Transformer models in predicting exchange rates on smaller datasets.
Transformer models showed potential for improvement with larger datasets and longer sequences.
Incorporating macroeconomic indicators significantly improved model accuracy.

## 📊 Results: Actual vs Predicted Forex Rates

### 1. LSTM Model
![image](https://github.com/user-attachments/assets/f35c2d8d-758f-4e00-871a-cdded2672a9e)

- **MSE**: 0.00051666
- **RMSE**: 0.0283
- LSTM closely follows the actual exchange rate trend with minimal error, especially effective for short-sequence data.

---

### 2. Transformer Model
![image](https://github.com/user-attachments/assets/875860ce-e290-476f-9e2d-9b990686f4f0)

- **MSE**: 0.00078637
- **RMSE**: 0.280
- Captures general trends, slightly less accurate than LSTM, but performs better with more data due to attention mechanisms.

---

### 3. Support Vector Regression (SVR)
![image](https://github.com/user-attachments/assets/0a3bc422-6011-48a9-9d3f-404ecec48a9d)


- **MSE**: 0.0021907
- **RMSE**: 0.0148
- SVR offers decent prediction but is limited in capturing volatile trends compared to deep learning models.
