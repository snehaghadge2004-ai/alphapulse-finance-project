AlphaPulse - Financial Risk & Volatility Analysis

 Project Overview
AlphaPulse is a financial analytics project that focuses on analyzing stock market data, measuring risk, and predicting future price behavior using statistical and simulation techniques.

---

##  **Week 1: Data Acquisition & Cleaning**

###  Objective
To collect historical stock data and preprocess it for analysis.

---

###  Tasks Performed
- Selected a diversified portfolio of stocks (AAPL, MSFT, GOOGL, AMZN, TSLA)
- Fetched historical stock data using Python
- Handled missing values and ensured data consistency
- Adjusted stock prices for splits and dividends
- Cleaned and structured the dataset for further analysis

---

###  Output
- Cleaned dataset (`clean_stock_data.csv`) ready for analysis
- Structured time-series data for multiple stocks


---

##  **Week 2: Quantitative Analysis**

###  Objective
To analyze stock performance using statistical and financial metrics.

---

###  Tasks Performed
- Calculated Daily Returns using price data
- Computed Volatility to measure risk
- Implemented NumPy-based calculations for efficiency
- Performed Monte Carlo Simulation (10,000 runs) to predict future portfolio value
- Analyzed distribution of returns (risk & variability)

---

###  Output
- Returns dataset (`returns.csv`)
- Volatility dataset (`volatility.csv`)
- Simulation-based insights for future stock behavior


---

##  **Week 3: Dashboard & Visual Storytelling**

###  Objective
To build an interactive Power BI dashboard for analyzing stock trends and enabling scenario-based insights.

---

###  Tasks Performed
- Imported cleaned stock data, returns, and volatility into Power BI
- Created visualizations:
  - Stock Price Trends 
  - Daily Returns 
  - Volatility 
- Designed a structured and user-friendly dashboard layout
- Added Date slicer for dynamic filtering
- Built relationships between datasets for consistent interaction
- Implemented What-if parameter (`Market Change`) to simulate market scenarios
- Created dynamic measure (`Adjusted_AAPL`) for scenario-based price changes

---

### Output
- Interactive Power BI dashboard (`.pbix`)
- Dynamic filtering and visualization
- Scenario simulation using What-if analysis

---

### Key Insight
The What-if analysis allows users to simulate market changes (e.g., ±10%) and instantly observe the impact on stock prices, enabling better decision-making and risk understanding.
---

Conclusion
This project demonstrates end-to-end financial data analysis, risk modeling, and simulation techniques, making it suitable for real-world financial analytics applications.
