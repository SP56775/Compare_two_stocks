#  Project 2: Stock Price Comparison — TCS vs INFY

Compare the stock performance of Tata Consultancy Services (TCS) and Infosys (INFY) using Python. This project focuses on analyzing and visualizing key stock indicators and trends.

---

##  Objective

Evaluate and compare two major Indian IT companies:
- Understand how TCS and INFY have performed over time
- Compare their daily returns, volatility, and overall trends
- Use both static and interactive visualizations for insights

---

##  5-Step Process

### 1. Define the Question
> How do TCS and INFY stocks compare in terms of returns, volatility, and trends over the last few years?

### 2. Collect the Data
- Fetched using [`yfinance`](https://pypi.org/project/yfinance/)
- Tickers: `TCS.NS`, `INFY.NS`
- Time period: January 2018 – June 2024

### 3. Clean the Data
- Removed missing values
- Aligned dates and merged data from both stocks
- Calculated:
  - Daily Returns
  - Cumulative Returns
  - Annual Returns

### 4. Analyze the Data
- Compared statistical summaries
- Detected high-volatility periods
- Compared investment growth through cumulative returns
- Analyzed trend direction using SMA and volatility

### 5. Visualize and Share Findings

** Visualizations and their Insights:**

- ** Closing Price Comparison**  
  → Price movement trends for both stocks over time

- ** Daily Returns**  
  → Distribution and comparison of short-term changes

- ** Cumulative Returns**  
  → Long-term investment growth comparison

- ** Rolling Volatility**  
  → Measures and compares risk between the two stocks

- ** Annual Returns Bar Plot (Plotly)**  
  → Interactive bar graph showing year-wise performance


### 1. Clone the repository
```bash
git clone https://github.com/SP56775/Compare_two_stocks.git
cd Compare_two_stocks/
