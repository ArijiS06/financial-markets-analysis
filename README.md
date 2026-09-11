# financial-markets-analysis
Python analysis of the performance, risk and correlations of major technology stocks and the S&P 500.
## Overview

This project uses Python to analyse the historical performance and risk characteristics of Apple, Microsoft, NVIDIA, Google and the S&P 500 from 2020 to the latest available market data.

The aim is to compare the assets not only by their historical price performance, but also by their volatility, drawdowns, correlations and risk adjusted performance.

## Technologies

- Python
- pandas
- yfinance
- Matplotlib
- Seaborn
- Google Colab

## Analysis

The project includes:

- Historical market data collection
- Daily return calculations
- Normalised price performance comparison
- Total return and CAGR
- Annualised volatility
- Maximum drawdown
- Correlation and covariance analysis
- Sharpe ratio
- Risk return visualisation
- Moving averages
- Rolling volatility
- Rolling correlation

## Key Findings

- NVIDIA generated the strongest overall growth during the analysis period, although this was accompanied by substantially higher volatility.

- The S&P 500 demonstrated lower volatility than the individual technology stocks, highlighting the potential risk-reduction benefits of broader diversification.

- Apple, Microsoft, NVIDIA and Google displayed positive return correlations, suggesting that holding several large technology companies alone may provide limited diversification.

- Maximum drawdown analysis showed that strong long-term performance did not prevent assets from experiencing substantial temporary losses.

- Risk-adjusted performance differed from absolute performance, demonstrating the importance of considering risk alongside return.

## Limitations

The analysis covers the period from 2020 to the latest available market data and results may differ across other time horizons.

The project primarily examines historical market price behaviour and does not model company fundamentals, macroeconomic variables or future expected returns.

Historical correlations are not assumed to remain constant, and the Sharpe ratio uses standard deviation as its measure of risk.

Historical performance does not guarantee future results.

## Project Notebook

The full Python analysis, calculations and visualisations are available in the Jupyter notebook contained in this repository.
