# Hourly Electricity Load Forecasting (PJM)

This project forecasts hourly electricity demand (MW) for the PJM Interconnection using historical load data.

The goal is to apply time-series feature engineering and machine learning (Random Forest) to model and predict short-term electricity load.

## Dataset
- **Source:** PJM Interconnection
- **Frequency:** Hourly
- **Target:** `PJM_Load_MW` (load in megawatts)
- **Period:** 1998–present

## Objectives
- Explore trends, seasonality, and volatility in load data
- Create lagged and rolling window features
- Apply time-aware cross-validation (`TimeSeriesSplit`)
- Train and evaluate tree-based model (Random Forest)
