# 💰 Financial Time-Series Analysis: Stock Comparison & Visualization

## 🎯 Project Overview & Business Value

This project provides a comprehensive framework for **comparing the historical performance of multiple equity assets** using advanced data visualization techniques. The goal is to derive actionable insights into market trends, volatility, and risk-adjusted returns, primarily for portfolio management.

**Key Deliverable:** An interactive visualization dashboard (built with **Plotly**) to track **[List 1-2 Key Metrics, e.g., Cumulative Returns and Daily Volatility]** over time.

## ⚙️ Technical Methodology & Metrics

1.  **Data Acquisition:** Used **[Specify Source, e.g., the `yfinance` library or API name]** to fetch adjusted close prices for tickers **[List 2-3 tickers analyzed, e.g., AAPL, GOOG, SPY]**.
2.  **Financial Metrics:** Calculated key time-series metrics:
    * **Daily Returns**
    * **Cumulative Returns** (To track growth over the period)
    * **Rolling Volatility** (A measure of risk)
3.  **Interactive Visualization:** Utilized **Plotly** to create interactive line plots and candlestick charts, enabling users to zoom and inspect specific periods.

## 📚 Project Files

* **[01\_Equity\_Viz\_Analysis.ipynb](https://github.com/pandakitty/Financial-Time-Series-Analysis/blob/main/notebooks/01_Equity_Viz_Analysis.ipynb)**: Complete analysis covering data fetching, metric calculation, and visualization generation.
* `requirements.txt`: List of all necessary Python packages.

## 🛠️ Stack & Tools

* **Language:** Python
* **Core Libraries:** Pandas (for time-series data manipulation), NumPy
* **Data Source:** [e.g., `yfinance` / `pandas-datareader`]
* **Visualization:** Plotly
