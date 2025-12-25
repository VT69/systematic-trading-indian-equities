# Signal-Based Systematic Trading Strategy on Indian Equities

## Overview
This project implements and evaluates a signal-based systematic trading strategy applied to a subset of liquid Indian equities. The focus is on strategy design, backtesting, and risk-aware performance evaluation rather than return maximization.

---

## Problem Statement
Predictive signals alone do not guarantee profitable trading strategies due to transaction costs, market regimes, and execution constraints. This project aims to:
- Translate predictive signals into systematic trading rules
- Evaluate performance using risk-adjusted metrics
- Assess robustness across market conditions

---

## Methodology
- Selected a universe of 10–15 liquid Indian equities (NIFTY 50 constituents)
- Engineered trading signals using technical indicators such as moving averages, RSI, and realized volatility
- Implemented a modular backtesting framework with daily rebalancing and position sizing
- Incorporated realistic transaction cost assumptions (10–20 bps per trade)
- Evaluated performance using Sharpe ratio, maximum drawdown, volatility, and cumulative returns

---

## Evaluation Approach
- Multi-year historical backtesting
- Rolling-window robustness analysis
- Regime-based performance evaluation (bull, bear, sideways markets)

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## Project Status
🚧 Under active development  
Planned features:
- Interactive web-based backtesting platform
- User-configurable strategy parameters
- Portfolio-level analytics dashboard

---

## Disclaimer
This project is for educational purposes only and does not constitute financial advice.
