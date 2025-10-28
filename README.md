
#  Portfolio Optimization with Sharpe Ratio

This project demonstrates how to construct and optimize an investment portfolio using Python and modern quantitative finance techniques.  
It focuses on finding the **optimal asset allocation** that maximizes the **Sharpe Ratio**, balancing return and risk across multiple assets.

---

##  Project Overview

Portfolio optimization is a core task in quantitative finance and investment management.  
The goal is to allocate capital across different assets (AAPL, MSFT, GOOGL, AMZN, TSLA) in a way that maximizes return per unit of risk.

In this project, we:
- Collected historical adjusted close prices from **Yahoo Finance**.
- Computed daily and annualized returns and volatilities.
- Simulated **15,000 random portfolios** using a **Monte Carlo approach**.
- Calculated the **Sharpe Ratio** for each portfolio.
- Identified the **optimal portfolio** with the maximum Sharpe Ratio.
- Visualized the **efficient frontier** and compared portfolio performance metrics.

The notebook is fully reproducible and structured for readability, suitable for both technical review and recruitment purposes.

---

##  Data & Methodology

- **Assets:** AAPL, MSFT, GOOGL, AMZN, TSLA  
- **Period:** 2019-01-01 to 2024-12-31  
- **Source:** Yahoo Finance via the `yfinance` Python library  
- **Methodology:**
  1. Data Cleaning & Normalization  
  2. Monte Carlo Simulation (15,000 portfolios)  
  3. Portfolio Expected Return & Volatility Calculation  
  4. Sharpe Ratio Computation  
  5. Optimization of weights to maximize Sharpe Ratio  
  6. Visualization of Efficient Frontier  

---

##  Results & Insights

- The **optimal portfolio** was found by maximizing the Sharpe Ratio, achieving the best trade-off between risk and return.  
- The **efficient frontier plot** shows the set of portfolios that offer the highest expected return for each level of risk.  
- Insights include how diversification among technology stocks affects portfolio volatility and the importance of correlation between assets.

*(Exact numerical results are available in the notebook.)*

---

## How to Run

Clone this repository and install dependencies:

```bash
git clone https://github.com/alejandrocanaless/sharpe.git
cd portfolio-optimization
pip install -r requirements.txt
