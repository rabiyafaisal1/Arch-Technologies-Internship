# Stock Price Prediction

Predicts next-day AAPL closing price using Linear Regression, based on 5 years of historical Open/High/Low/Close/Volume data.

**Result:** R² of 0.987, average prediction error (MAE) of $2.17

**Key finding:** The model's strength largely reflects a market truth; stock prices move gradually rather than erratically, so today's price is a powerful predictor of tomorrow's.

**Tools:** Python, yfinance, pandas, scikit-learn, matplotlib, Google Colab

**Workflow:** data retrieval (yfinance) → feature engineering (next-day target creation) → chronological train/test split (no shuffling, since order matters for time series) → Linear Regression → evaluation (MAE, RMSE, R²) → actual vs. predicted visualization
