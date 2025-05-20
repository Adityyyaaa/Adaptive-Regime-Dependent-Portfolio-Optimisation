# Adaptive Regime Portfolio Optimization

This repository contains the implementation of the thesis project:  
**"Regime-Dependent Portfolio Optimization: An Integrated Framework of Statistics, Risk-Parity and Deep Learning"**  

## 📘 Abstract

In an era of rapidly shifting market conditions, static portfolio optimization models fall short in capturing structural market transitions. This project introduces a **regime-switching portfolio optimization framework** using **Hidden Markov Models (HMMs)** to detect market regimes and adaptively rebalance portfolios using a combination of traditional financial models and deep learning approaches.

## 🧠 Key Features

- **Regime Detection using HMMs**
- **Dynamic Portfolio Switching** based on market regimes
- **Integration of Multiple Portfolio Strategies**:
  - Markowitz Mean-Variance (MVP)
  - Hierarchical Risk Parity (HRP)
  - Autoencoder-based Deep Learning Optimization
  - Black-Litterman blended with Conditional Value-at-Risk (CVaR)

## 📊 Methodology Overview

1. **Data Acquisition**: NSE sectoral data (2018–2022) via Yahoo Finance APIs using `pandas-datareader`.
2. **Static Portfolio Strategies**: Implemented and benchmarked MVP, HRP, and Autoencoder-based methods.
3. **Adaptive Strategy**:
    - Regime identification via HMM
    - Regime-specific portfolio allocation using CVaR/MVP
    - Walk-forward testing approach for rebalancing
4. **Performance Metrics**:
    - Annual Return
    - Annual Volatility
    - Sharpe Ratio


## 📈 Sectors Covered

Portfolios are constructed for the following **10 NSE Thematic Sectors**:

- NIFTY Commodities
- NIFTY Energy
- NIFTY Manufacturing
- NIFTY Services
- NIFTY MNC
- NIFTY Transportation & Logistics
- NIFTY Infrastructure
- NIFTY Housing
- NIFTY Consumption
- NIFTY 100 ESG

## 🛠️ Technologies Used

- Python 3.10+
- Libraries: `numpy`, `pandas`, `scikit-learn`, `hmmlearn`, `keras`, `matplotlib`, `seaborn`, `pypfopt`
- Data: Yahoo Finance API, NSE sectoral compositions

## 📬 Contact

For questions or collaborations, reach out to:
📧 whyaditya07@gmail.com

