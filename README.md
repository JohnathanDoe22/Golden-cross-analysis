# Golden Cross Analysis

Analysis of 50/200-day EMA crossovers to identify momentum shifts and trend reversals in equity markets.

## Scripts

### `50_200_crossover_analysis.py`
Visualization of 50/200-day EMA crossovers with Golden Cross and Death Cross signals

### `tactical_allocation_backtest.py`
Comprehensive tactical allocation strategy backtesting

## What It Does

### Visualization Script
Plots price charts with 50-day and 200-day EMAs to visually identify trend changes:
- **Golden Cross**: 50-day EMA crosses above 200-day EMA (bullish signal)
- **Death Cross**: 50-day EMA crosses below 200-day EMA (bearish signal)

### Backtesting Analysis
Tests tactical allocation strategies using EMA crossover signals against systematic balanced portfolio approaches:
- Compares trend-following tactical strategy (13/52-week EMAs with 55-65% stock allocation bands)
- Benchmarks against monthly rebalanced 60/40 portfolios
- Uses S&P 500 and 10-year Treasury data from 1970 onwards
- Provides comprehensive performance metrics:
 - Total returns and annualized returns
 - Volatility and Sharpe ratios
 - Maximum drawdowns

## Requirements

```bash
pip install yfinance pandas matplotlib
