
# JetRail Traffic Forecasting 🚄

## Overview

Investors need insights into the viability of a new high-speed transportation system — **JetRail**, which uses jet propulsion technology to move people at rapid speeds. JetRail holds the patent for its tech, but the success of a large-scale rollout depends on gaining traction: more than **1 million monthly users within the next 18 months**.

To support this decision-making, this project aims to **forecast monthly JetRail traffic** for the next 7 months using historical data.

## Objective

Help **Unicorn Ventures** — a VC firm investing in early-stage B2C startups — determine whether JetRail can meet its user growth goals. If the forecasts show promising growth, it could justify a **pre-series A funding round**.

## Dataset

Historical traffic data is provided from JetRail’s inception, covering:

- Monthly passenger traffic
- Date-wise timestamps

## Technologies Used

- Python
- Pandas
- Matplotlib / Seaborn
- Statsmodels
- Facebook Prophet
- ARIMA modeling

## 📈 Results

After thorough analysis and modeling of the time series data, the following steps and findings were achieved:

### 🔍 Trend & Seasonality Analysis
- The underlying **trend** and **seasonal patterns** in JetRail traffic were identified and analyzed to understand historical user behavior.

### 🧪 Forecasting Techniques Applied
Four different time series forecasting methods were implemented and evaluated:

1. **Naive Approach** – Assumes the next value is the same as the last observed.
2. **Moving Average** – Uses the average of previous time steps for smoothing predictions.
3. **Simple Exponential Smoothing** – Applies exponentially decreasing weights to past observations.
4. **Holt’s Linear Trend Model** – Extends exponential smoothing to capture trends over time.

### 📊 Forecast Generation
- Forecasts were produced for the **next 7 months** to project future traffic volumes.
- Visualizations clearly illustrated the forecasted user growth trend.

### ✅ Business Insight
These forecasting insights provide a **data-driven foundation** to assess whether JetRail is on track to exceed **1 million monthly users**, guiding **Unicorn Ventures’ investment decision**.



---
