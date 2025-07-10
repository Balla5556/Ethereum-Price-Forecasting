# Ethereum-Price-Forecasting
Time series forecasting of Ethereum using technical indicators and regression models

# Ethereum Price Forecasting

📊 A capstone project for time series forecasting of Ethereum returns using engineered technical indicators and machine learning models.

---

## 🔧 Tools & Tech
- Python, Pandas, NumPy
- Alpha Vantage API (data extraction)
- RSI, Moving Averages, Autocorrelation
- Regression Models: Linear, Ridge, Lasso, Voting Regressor
- Matplotlib, Seaborn

---

## 📊 Objective
Predict 40-day forward returns of Ethereum using historical price data and technical indicators to aid trading strategy design.

---

## 🧪 Approach
1. Pulled daily ETH data via Alpha Vantage API
2. Engineered indicators: RSI, SMA, EMA, volatility, autocorrelation
3. Prepared target variable: 40-day forward return
4. Trained and evaluated multiple regression models:
   - Linear Regression
   - Ridge & Lasso
   - Voting Regressor (Ensemble)

5. Evaluated using MAE, RMSE, and R²

---

## ✅ Results
- Voting Regressor achieved the best predictive accuracy with the lowest RMSE.
- 40-day return predictions showed correlation with momentum signals (RSI, volatility clusters).

---

## 📁 Files
- `eth_forecast_model.ipynb`: Main modeling notebook
- `alpha_data_fetch.py`: Script to pull data from Alpha Vantage
- `utils.py`: Custom feature engineering functions

---

## 🔗 Demo & Visuals
_Add charts or dashboard screenshots here (or paste in the notebook)._

---

## 📬 Contact
Made by Sai Chaitanya Balla  
[LinkedIn](https://www.linkedin.com/in/sai-chaitanya-balla)
