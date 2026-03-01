#  S&P 500 Stock Market Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

---

##  Project Overview

This project performs a comprehensive analysis of historical stock data from S&P 500 companies. The objective is to explore stock behavior, sector-level trends, volatility patterns, and relationships among companies using real-world financial data.

The dataset combines:

- Company-level information scraped from Wikipedia  
- Historical daily stock price data scraped from Yahoo Finance  

Through Exploratory Data Analysis (EDA), statistical analysis, visualization, and feature engineering, this project uncovers meaningful insights into U.S. stock market dynamics.

---

##  Objectives

- Scrape and integrate S&P 500 company information  
- Collect historical daily stock prices  
- Perform data cleaning and preprocessing  
- Conduct exploratory data analysis (EDA)  
- Analyze stock price distributions and volatility  
- Examine sector-level performance  
- Engineer financial features such as daily returns  
- Detect and interpret outliers  
- Generate insights about overall market behavior  

---

##  Dataset Information

**Dataset Name:** `sp500_stock_with_market.csv`  
**Total Records:** ~126,000  
**Companies Covered:** 503 S&P 500 companies  
**Time Span:** ~1 year of daily trading data (~250 trading days)

###  Features Included

- Date  
- Ticker  
- Company  
- Sector  
- Founded  
- Open  
- High  
- Low  
- Close  
- Adj Close  
- Volume  
- Year  
- Month  
- Day  
- Age (Company age)  
- Return (Daily percentage return)  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- BeautifulSoup (Web Scraping)  
- Requests  
- Selenium  
- Concurrent Futures  

---

##  Project Structure
- ├── Team_6_Midterm_Project.ipynb
- ├── sp500.csv
- ├── sp_market.csv
- ├── sp500_stock_with_market.csv
- └── README.md



---

##  How to Run the Project

###  Option 1: Run Using Existing Dataset (Recommended)

1. Open `Team_6_Midterm_Project.ipynb`
2. Run from the data loading section
3. Execute the notebook sequentially

---

###  Option 2: Run Full Web Scraping

Install required packages:

```bash
pip install requests beautifulsoup4 pandas yfinance selenium webdriver-manager


Then run the notebook from top to bottom.

## Exploratory Data Analysis Highlights



✔ Data Quality

No missing values

No duplicate records

503 unique companies

11 sectors represented

✔ Statistical Insights

Significant variability in stock prices across companies

Trading volume shows high dispersion

Price distributions are right-skewed

✔ Feature Engineering

Extracted Year, Month, Day from Date

Created Company Age feature

Calculated Daily Returns per ticker

✔ Outlier Detection

High-priced stocks identified using IQR method

Outliers confirmed as valid market behavior

📈 Key Insights

Stock prices vary significantly across sectors.

Market trading volume occasionally shows extreme spikes.

Individual stock volatility is higher than overall market stability.

Sector distribution shows Industrials as highly represented.

Daily returns behave consistently with expected financial patterns.

🔮 Future Improvements

Time series forecasting (ARIMA, LSTM)

Volatility clustering analysis

Portfolio optimization

Risk-adjusted performance metrics (Sharpe Ratio, CAPM)

Sector-based investment comparison
