# Stock Price and Revenue Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![pandas](https://img.shields.io/badge/pandas-data%20analysis-green)
![matplotlib](https://img.shields.io/badge/matplotlib-visualization-orange)

This project analyzes stock price and revenue data for **Tesla** and **GameStop** using Python.  
The goal is to compare stock market behavior with company revenue trends using data visualization.

---

## Tools and Libraries

- 🐍 **Python**
- 📊 **pandas** – data manipulation and analysis
- 📈 **matplotlib** – data visualization
- 💹 **yfinance** – stock price data from Yahoo Finance

---

## Data Sources

The following data sources were used in this project:

- **Stock Price Data**  
  - Source: **Yahoo Finance**  
  - Retrieved using the `yfinance` Python library

- **Revenue Data**  
  - Source: **Macrotrends**  
  - Revenue tables were manually extracted as the website restricts automated scraping

---

## Data Files Used

The following files are included in this repository:

- `Stock_Price_Revenue_Analysis.ipynb` – Main analysis notebook  
- `tesla_revenue.csv` – Tesla quarterly revenue data  
- `gamestop_revenue.csv` – GameStop quarterly revenue data  

---

## Methodology

- Stock price data was collected using Yahoo Finance
- Revenue data was manually extracted from Macrotrends and saved as CSV files
- Data was cleaned and aligned based on time periods
- Dashboard-style visualizations were created to compare stock price and revenue trends

---

## Key Observations

- Tesla’s stock price generally aligns with its revenue growth
- GameStop’s stock price shows high volatility that does not match its revenue trend
- Stock prices are influenced by factors beyond revenue alone

---

## Conclusion

This project demonstrates how data visualization can be used to compare business performance
with stock market behavior using real-world financial data.  
It highlights the difference between company fundamentals and market movements.
