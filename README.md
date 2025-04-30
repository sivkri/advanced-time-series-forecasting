# Advanced Time Series Forecasting

A comprehensive Jupyter notebook covering classical statistical methods, machine learning, deep learning, and transformer-based approaches for time series forecasting. This project also includes interpretability, hyperparameter tuning, and ensembling techniques.

---

## Key Features

- Missing value handling & outlier detection
- Exploratory analysis with ACF/PACF and decomposition
- Classical models: ARIMA, ETS
- Machine learning models: XGBoost, RandomForest, SVR
- Deep learning models: LSTM, BiLSTM, LSTM+Dense, Autoencoder
- Transformer-based forecasting
- Facebook Prophet and Kats support
- Hyperparameter tuning (Optuna)
- Model stacking and ensembling
- SHAP-based explainability
- Export predictions and visualizations
- Model evaluation & comparison dashboard

---


## Setup Instructions

```bash
# Create environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install required packages
pip install -r requirements.txt
```

---

## Run Notebook

Use Jupyter or VS Code to open:
```bash
Time_series_ML_and_DL_Enhanced.ipynb
```

---

## Output

- Forecast plots
- Attention heatmaps
- Exported CSV of predictions
- Evaluation metrics (MAE, RMSE, MAPE)

---

## Future Enhancements

- Streamlit dashboard
- AutoML integration
- Multivariate forecasting
- Model monitoring pipeline
