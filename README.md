
# Portfolio Optimization with Sharpe Ratio

## Overview
This project implements Modern Portfolio Theory to optimize asset allocation 
using historical stock data from major tech companies (AAPL, MSFT, GOOGL, AMZN, TSLA).

##  Key Features
- Monte Carlo simulation (15,000 scenarios)
- Sharpe Ratio optimization
- Efficient Frontier visualization
- 5-year historical data analysis (2019-2024)

##  Results
- **Optimal Portfolio Weights:**
  - AAPL: 49.3%
  - MSFT: 21.7%
  - TSLA: 27.8%
  - Others: < 1%

## Technologies
- Python 3.9
- pandas, numpy, matplotlib
- yfinance for data retrieval
- scipy for optimization

##  Execution
```bash
pip install -r requirements.txt
jupyter notebook Portfolio_Optimization_Final.ipynb
