# Time-series-stock-forecasting-analysis

# 📈 Time Series Forecasting & Investment Analysis

## Overview

This project applies time series forecasting techniques to real-world stock market data to analyze price behavior, volatility, seasonality, and diversification strategies. The goal is to evaluate model performance across multiple stocks and derive actionable investment insights.

Three publicly traded companies from different industries were analyzed:
- **AAPL (Apple)** — Technology  
- **NVDA (NVIDIA)** — Semiconductors  
- **TSLA (Tesla)** — Automotive / Energy  

The project demonstrates how different industries exhibit different market dynamics and forecasting behavior.

---

## Business Objective

- Forecast stock price trends using ARIMA and SARIMA models  
- Compare seasonal vs non-seasonal forecasting performance  
- Evaluate volatility, predictability, and diversification benefits  
- Provide data-driven portfolio diversification insights  

---

## Methods

- Time series data collection and preprocessing  
- Trend and seasonality analysis  
- ARIMA and SARIMA model development  
- Train-test split (70% training / 30% testing)  
- Model tuning and evaluation  
- Residual diagnostics and error analysis  

---

## Key Findings

- **ARIMA outperformed SARIMA for Tesla (TSLA)**, indicating price movements driven more by macroeconomic factors, company news, and investor sentiment than seasonal patterns.
- **SARIMA improved forecasting accuracy for NVDA and META**, demonstrating strong cyclical and seasonal behavior.
- Tech stocks within the same sector (AAPL, MSFT, GOOGL) showed **high correlation**, increasing portfolio risk.
- Diversifying across industries significantly reduced portfolio volatility and improved risk-adjusted stability.

---

## Model Performance

Models were evaluated using:
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R-squared (R²)  
- Residual diagnostics  

The analysis demonstrated that model performance varies significantly by sector and stock behavior.

---

## Investment Insights

- Sector diversification is critical for long-term portfolio stability  
- Some stocks exhibit predictable seasonal cycles (better for tactical trading)  
- Others are driven by external shocks and macro trends (better for long-term positioning)  

---

## Tools

- Python (pandas, numpy, statsmodels, matplotlib, seaborn, scikit-learn)  
- Google Colab  

---

## Interactive Notebook

View the full analysis, forecasting models, and visualizations here:

🔗 **Google Colab Notebook:**  
[https://colab.research.google.com/drive/1lxckFtmC0K9IFuUg4_M55rNN3hkNjszc](https://colab.research.google.com/drive/1lxckFtmCOK9lFuUg4_M55rNN3hkNjscz#scrollTo=F-Pba2PQctsi)

---

## Academic Context

This project was completed as part of a Time Series Forecasting course focused on applying predictive modeling to real-world financial data. Emphasis was placed on model interpretation, business relevance, and investment decision-making.
