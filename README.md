AlphaPulse - Financial Risk & Volatility Analysis

📌 Project Overview
AlphaPulse is a financial analytics project that focuses on analyzing stock market data, measuring risk, and predicting future price behavior using statistical and simulation techniques.

---

# 🟢 Week 1: Data Collection & Cleaning

Objective
To collect and preprocess stock market data for analysis.

Tasks Performed
- Selected stocks: AAPL, MSFT, GOOGL, TSLA, AMZN
- Fetched historical data using yfinance
- Applied auto-adjustment for accurate pricing
- Extracted closing prices
- Handled missing values using dropna()
- Saved clean dataset as CSV

Output
- Clean and structured dataset ready for analysis

---

🟡 Week 2: Quantitative Analysis

Objective
To analyze stock behavior, measure risk, and simulate future price movements.

Tasks Performed

1. Daily Returns
- Calculated percentage returns using pct_change()
- Cleaned data using dropna()

2. Correlation Analysis
- Created heatmap using seaborn
- Identified relationships between stocks
- Used for diversification insights

3. Volatility Analysis
- Calculated 30-day rolling standard deviation
- Visualized risk levels across stocks

4. Monte Carlo Simulation
- Simulated 1000 possible future price paths
- Predicted stock behavior over 1 year
- Used NumPy for random sampling

5. Statistical Validation
- Generated histogram of final prices
- Calculated skewness and kurtosis
- Analyzed distribution and risk patterns

---

🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

---

📊 Key Insights
- Highly correlated stocks increase portfolio risk
- Volatility helps measure uncertainty
- Monte Carlo simulation provides probabilistic forecasts
- Statistical metrics validate model behavior

---

🚀 Future Work
- Build interactive dashboard (Power BI / Tableau)
- Add portfolio optimization
- Enhance prediction models

---

# 📌 Conclusion
This project demonstrates end-to-end financial data analysis, risk modeling, and simulation techniques, making it suitable for real-world financial analytics applications.
