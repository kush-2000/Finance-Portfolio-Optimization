<p align="center">
  <img src="https://brand.utexas.edu/sites/default/files/images/logos/mccombs_fullcolor_horizontal.png" alt="McCombs School of Business" width="400"/>
</p>

# 📈 Investment Insiders: Portfolio Optimization

This project analyzes and optimizes a $45M client portfolio using quantitative methods to reduce risk and/or enhance returns. We implemented three portfolio strategies—Global Minimum Variance (GMV), Efficient Portfolio, and Optimal Risky Portfolio (ORP)—to provide tailored reallocation recommendations.

## 🧠 Objective
Provide strategic investment guidance by evaluating the client’s current portfolio and identifying optimal reallocation strategies based on risk tolerance and return goals.

## 🔧 Tools & Libraries
- **Python**: Primary language for analysis  
- **yfinance**: For historical sector ETF data  
- **NumPy, Pandas**: Data manipulation and matrix calculations  
- **Matplotlib, Seaborn**: Capital Allocation Diagram & visualizations

## 🗂️ Methodology

### 1. Data Collection
- Collected monthly ETF returns for 11 sectors using Yahoo Finance (Aug 2018–Sep 2024)
- Cleaned and prepared the dataset for analysis

### 2. Portfolio Metric Calculation
- Computed expected returns, standard deviations, and the Sharpe Ratio
- Constructed correlation and covariance matrices

### 3. Optimization Techniques
- **GMV Portfolio**: Lowest volatility; recommended for risk-averse clients
- **Efficient Portfolio**: Matches original return with reduced risk
- **ORP (Optimal Risky Portfolio)**: Maximized Sharpe Ratio; ideal for clients seeking higher returns

### 4. Capital Allocation Diagram (CAD)
- Visualized the efficient frontier, Capital Allocation Line, and portfolio options for comparison

## 📊 Results Summary

| Portfolio Type         | Expected Return | Std. Deviation | Sharpe Ratio |
|------------------------|----------------:|---------------:|--------------:|
| Original Portfolio     | 13.37%          | 5.40%          | 0.16          |
| GMV Portfolio          | ~11.0%          | **3.48%**      | Higher        |
| Efficient Portfolio    | **13.37%**      | **3.60%**      | Improved      |
| Optimal Risky Portfolio| **36.17%**      | ~5.4%          | **Maximized** |

## ✅ Recommendations
- **Conservative**: Transition to GMV portfolio for stability
- **Balanced**: Efficient Portfolio retains return, reduces risk
- **Aggressive**: ORP offers the highest reward per unit of risk

## 📌 Team
Kush Patel and Saaket Joshi  
*MSBA Program, McCombs School of Business – Hook 'em!*
