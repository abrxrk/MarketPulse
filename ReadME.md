# MarketPulse – Financial Data Automation & Dashboard

## Overview
MarketPulse automates fetching live FX and stock market data, calculates key KPIs
(daily % change, volatility, moving averages), and visualizes them in a finance-grade web dashboard.

## Features
- Automated FX & stock data pipeline (USD/INR, EUR/USD, AAPL)
- Data cleaning & KPI calculations (rolling averages, volatility)
- Interactive Streamlit dashboard with KPI cards & Plotly charts
- One-click deployment via Streamlit Cloud

## Tech Stack
Python, Pandas, yfinance, Plotly, Streamlit

## Screenshots
*(Add here)*

## Run Locally
```bash
git clone <repo-url>
cd MarketPulse
pip install -r requirements.txt
streamlit run app.py
