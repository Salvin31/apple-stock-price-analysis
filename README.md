# Apple Stock Price Analysis and Forecasting Using Python

## Overview

This project presents an end-to-end analysis of **Apple Inc. (AAPL)** stock price data using Python. The objective is to analyze historical stock performance, identify market trends through technical indicators, and generate short-term forecasts using time-series modeling.

The project demonstrates the complete analytical workflow, including data acquisition, preprocessing, exploratory data analysis (EDA), feature engineering, visualization, and forecasting.

---

## Problem Statement

Financial markets generate large volumes of historical price data that can be analyzed to identify trends and support investment decisions. This project explores Apple's historical stock performance by applying data analysis and forecasting techniques to answer the following questions:

* How has Apple's stock price changed over time?
* What trends can be identified using moving averages?
* What insights can be gained from daily returns?
* Can historical data be used to forecast future stock prices?

---

## Dataset

Historical stock market data was retrieved directly from **Yahoo Finance** using the `yfinance` Python library.

**Company:** Apple Inc. (AAPL)

**Time Period:** Five Years

**Frequency:** Daily

The dataset contains:

* Open Price
* High Price
* Low Price
* Close Price
* Adjusted Close Price
* Trading Volume

---

## Project Objectives

The objectives of this project are to:

* Collect historical stock price data using Python.
* Perform exploratory data analysis.
* Clean and prepare financial data for analysis.
* Visualize historical stock price movements.
* Calculate technical indicators commonly used in financial analysis.
* Forecast future stock prices using the ARIMA model.

---

## Tools and Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* yfinance
* Statsmodels

---

## Methodology

### 1. Data Collection

Historical stock price data was downloaded programmatically from Yahoo Finance using the `yfinance` package.

### 2. Data Exploration

The dataset was examined to understand its structure through:

* Dataset dimensions
* Data types
* Summary statistics
* Missing value analysis

### 3. Data Preprocessing

The preprocessing stage included:

* Converting dates into the appropriate format
* Handling missing values
* Preparing the dataset for analysis

### 4. Exploratory Data Analysis

The notebook explores historical trends through visualizations including:

* Closing price over time
* Market performance during the AI boom period
* Daily percentage returns

### 5. Technical Analysis

The following indicators were calculated:

* 50-Day Simple Moving Average (SMA)
* 200-Day Simple Moving Average (SMA)
* 50-Day Exponential Moving Average (EMA)

These indicators help identify long-term and short-term market trends.

### 6. Time-Series Forecasting

An **ARIMA (AutoRegressive Integrated Moving Average)** model was implemented to forecast Apple's stock price for the next 30 trading days based on historical closing prices.

---

## Key Analyses

The project includes analyses such as:

* Historical stock price trends
* Daily return analysis
* Moving average comparison
* Trend identification
* Time-series forecasting
* Forecast visualization

---

## Skills Demonstrated

This project demonstrates practical experience with:

* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Financial Data Analysis
* Feature Engineering
* Data Visualization
* Time-Series Analysis
* Forecasting using ARIMA
* Python Programming

---

## Project Structure

```text
apple-stock-price-analysis/
│
├── Apple_Stock_Price_Analysis.ipynb
├── README.md
```

---

## Installation

Install the required libraries before running the notebook.

```bash
pip install pandas numpy matplotlib yfinance statsmodels
```

---


## Results

The analysis highlights Apple's long-term market performance and demonstrates how technical indicators can be used to evaluate price trends. The ARIMA forecasting model provides a basic statistical approach to predicting future stock prices using historical observations.

This project illustrates the application of Python in financial analytics and serves as a foundation for more advanced forecasting techniques.

---

## Future Enhancements

Potential improvements include:

* Comparing multiple technology companies
* Implementing additional technical indicators such as RSI, MACD, and Bollinger Bands
* Developing LSTM-based deep learning forecasting models
* Building an interactive dashboard using Streamlit or Dash
* Evaluating forecasting accuracy using additional performance metrics

---

## Author

**Salvin Thomas**

MBA in Business Analytics

Aspiring Data Analyst | Python | SQL | R | Power BI | Tableau

---

## License

This project is intended for educational and portfolio purposes.
