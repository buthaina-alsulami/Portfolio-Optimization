# Portfolio Optimization & Risk Analysis Tool

A Python tool to optimize stock portfolios using **Sharpe Ratio maximization**. This project allows to pull historical market data, analyzing risk, and identifying optimal allocations.

---

## Key Features

- **Data Sourcing:** Automatically pulls historical stock data via Yahoo Finance.
- **Optimization:** Uses `scipy.optimize` to maximize Sharpe Ratio for an optimal risk-return tradeoff.
- **Benchmarks:** Compares portfolio performance against the S&P 500 (`^GSPC`).
- **Visualizations:** Includes correlation heatmaps, cumulative return plots, and risk-return scatter plots.
- **Risk Management:** Constrains individual asset weights to prevent over-concentration and promote diversification.

---

## Performance Metrics

- **Expected Annual Return:** Projected portfolio return based on historical or forward-looking estimates.  
- **Annual Volatility:** Measures portfolio risk.  
- **Portfolio Beta:** Sensitivity to market movements.  
- **Portfolio Alpha:** Excess return relative to the benchmark.  

---

## Example Usage

The tool calculates **optimal weights** for each asset, constrained between 10% and 30% per stock, ensuring diversification and avoiding over reliance on a single position.  


Analysis Example

The tool calculates optimal weights (with constraints to avoid single-stock dominance) to create a well-diversified allocation that aligns with risk-return objectives.
