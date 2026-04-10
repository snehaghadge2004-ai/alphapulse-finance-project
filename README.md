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

##  **Week 4: Finalization**

###  Objective
To finalize the project by creating an executive summary dashboard and presenting key financial insights using high-level KPIs.

---

###  Tasks Performed
- Created an **Executive Summary** page in Power BI
- Added KPI cards for key metrics:
  - Average Return
  - Volatility
  - Maximum Stock Price
  - Value at Risk (VaR - 5%)
  - Maximum Drawdown
- Implemented DAX measures for advanced KPIs:
  - VaR using percentile calculation
  - Max Drawdown using minimum return
- Ensured proper formatting and readability of KPI values
- Aligned and structured visuals for a clean and professional layout
- Verified all dashboard interactions (filters, slicers, What-if analysis)
- Performed manual data refresh to simulate real-world data updates

---

###  Output
- Final Power BI dashboard with:
  - Executive Summary page
  - KPI-based insights for performance and risk analysis
- Clean, interactive, and presentation-ready dashboard

---

###  Key Insight
The executive summary provides a quick overview of portfolio performance and risk using KPIs like returns, volatility, Value at Risk, and drawdown, enabling better decision-making.

---

###  Conclusion
The project was successfully completed with end-to-end implementation, including data processing, financial analysis, interactive visualization, and executive-level reporting.


