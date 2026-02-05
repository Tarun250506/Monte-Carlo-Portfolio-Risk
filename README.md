# Monte-Carlo-Portfolio-Risk-nalysis
### Objective
Quantify portfolio downside risk using Monte Carlo simulation, with emphasis on
probability of loss, maximum drawdown, Value at Risk (VaR), and Conditional VaR (CVaR).
### Methodology
- Modeled stochastic returns using assumed return distributions
- Simulated thousands of return paths over a fixed investment horizon
- Constructed cumulative price paths from simulated returns
- Computed downside-focused risk metrics (loss probability, drawdown, VaR, CVaR)
- Visualized distributional and path-dependent risk
### Key Insights
- Volatility alone fails to capture tail and path-dependent risk
- Drawdowns reveal peak-to-trough risk invisible in single-period returns
- CVaR provides more informative tail-risk assessment than VaR
### Assumptions & Limitations
- Returns are assumed to follow a normal distribution
- Does not model correlation across multiple assets
- Results are illustrative, not predictive
### Possible Extensions
- Fat-tailed return distributions (e.g., Student-t)
- Multi-asset portfolios with correlated returns
- Regime-switching or stress-scenario modeling

