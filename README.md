# MacroDrivenStressTestingSimulator
# Macro-Stress Portfolio Simulator

A Python-based simulator to test how a diversified Indian stock portfolio reacts to macroeconomic shocks using:

- Crude Oil prices (BZ=F)
- USD/INR exchange rates
- India VIX volatility index

## 📌 Key Features
- Stress scenario simulation (e.g., +63% oil spike, +75% VIX spike)
- Linear regression risk model
- VaR and CVaR (99% confidence)
- Rolling VaR
- Sharpe Ratio, Max Drawdown
- Visualizations for risk evolution

## 🛠️ Tools Used
- Python
- pandas, numpy
- yfinance, statsmodels
- matplotlib, seaborn

## 📁 Structure
- `notebook/`: Jupyter notebook with full analysis
- `data/`: Input macro and stock CSVs
- `plots/`: Visuals for Rolling VaR, cumulative returns, etc.

## 🧠 Insight
This project helps diagnose how vulnerable a portfolio is to systemic macro shocks and is useful for risk managers and portfolio analysts.

## ✅ Future Work
- Try non-linear models (XGBoost, LSTM)
- Include more macro variables (GDP, Repo Rate)
- Incorporating advanced risk models like Copula

