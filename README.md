# Ethereum Price Prediction using Feature Engineering

## Objective
To analyze Ethereum price data and engineer advanced features for future modeling and forecasting.

## Project Summary
This project processes Ethereum historical data (2018–present) to:
- Clean and prepare time-series price data
- Engineer over 20 financial features (returns, moving averages, volatility, z-scores)
- Visualize market behaviors using moving averages and return distributions
- Set a foundation for advanced predictive models (e.g., LSTM, XGBoost)

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, NumPy
- **Tools:** Jupyter Notebook

## Key Steps
- Combined date and time into a single `Datetime` column
- Handled missing values using forward-fill
- Engineered features like:
  - Daily % returns
  - Moving Averages and their slopes
  - Rolling Z-Scores
  - Close Percentiles (1, 3, 7, 20, 40-day)
- Visualized data distributions and trends

## Sample Visuals
- Close price vs moving averages
- Distribution of daily returns
- Feature comparison plots

## File Structure
- `ethereum_forecasting_pipeline.ipynb`: Main notebook with code and plots
- `Ethereum_2018_To_Present.txt`: Raw dataset (CSV format)
- `/figures`: (optional) Add output plots here for better presentation

## Future Work
- Apply ML models like LSTM, XGBoost for return prediction
- Deploy using Streamlit or Flask for real-time forecasting

## Contact
Sai Chaitanya Balla  
📧 ballasaichaitanya03@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/sai-chaitanya-balla)
