# 🌍 Climate Trend Analyzer

Analyzes 65 years of historical climate data (1960–2024) across 5 Indian cities to identify temperature trends, rainfall patterns, seasonal anomalies, and forecasts temperature up to 2050.

## 📊 Project Overview

| Item | Details |
|---|---|
| Dataset | Synthetic — 3,900 monthly records, 5 cities, 65 years |
| Cities | Mumbai, Delhi, Bangalore, Chennai, Kolkata |
| Model | Linear Regression (temperature forecasting) |
| Anomaly Detection | Z-Score method (threshold: 2σ) |
| Libraries | pandas, numpy, matplotlib, seaborn, scikit-learn, scipy |

## 🔍 What This Project Does

- Simulates 65 years of climate data with real-world warming trends and El Niño events
- Detects **temperature anomaly years** (1998, 2010, 2016, 2020) using Z-score
- Forecasts temperature through **2050** using Linear Regression
- Reveals seasonal heatmaps and decade-by-decade warming patterns

## 📈 Key Findings

- Total warming detected: **+1.32°C since 1960**
- Warming rate: **+0.30°C per decade**
- 4 anomaly years detected (all real El Niño events)

## 📈 Output Charts

### Temperature Trend
![Temp Trend](chart1_temp_trend.png)

### Anomaly Detection
![Anomalies](chart4_anomalies.png)

### Forecast to 2050
![Forecast](chart5_forecast_decades.png)

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy, SciPy
- Matplotlib, Seaborn
- Scikit-learn

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

Open `Climate_Trend_Analyzer.ipynb` in Jupyter and run all cells.

## 📁 Files

| File | Description |
|---|---|
| `Climate_Trend_Analyzer.ipynb` | Main notebook |
| `climate_data.csv` | 3,900-row climate dataset |
| `forecast_2025_2050.csv` | Temperature forecast output |
| `chart4_anomalies.png` | Z-score anomaly detection chart |
| `chart5_forecast_decades.png` | Forecast + decade comparison |
