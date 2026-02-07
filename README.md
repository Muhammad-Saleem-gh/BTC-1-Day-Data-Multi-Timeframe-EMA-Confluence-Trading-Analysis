# BTC-1-Day-Data-Multi-Timeframe-EMA-Confluence-Trading-Analysis
This repository contains a Python script for analyzing Bitcoin (BTC/USDT) price action using multi-timeframe EMAs, previous day levels, session highs/lows, trendlines, and trade confluence strategies.

---

## Features

- Multi-Timeframe Aggregation: Converts 5-minute candles into 1H and 4H timeframes for higher timeframe analysis.

- Previous Day Levels: Calculates High, Low, and Close of the previous day for support/resistance analysis.

- Trading Sessions: Identifies key sessions (Asian, London, New York) and their high/low ranges.

- EMA Analysis: Computes EMA20 and EMA50 for trend direction, pullbacks, and support/resistance zones.

- EMA Reactions: Detects price reactions, breaks, and retests of EMAs.

- Confluence Signals: Combines EMAs, previous day levels, session highs/lows, trendlines, liquidity sweeps, and Fair Value Gaps (FVG)    for stronger signals.

- Trade Setup Suggestions: Provides Entry, Stop Loss, and Take Profit levels based on EMA setups.

- Confluence Scoring: Quantifies the strength of trade signals with a multi-layer confluence score.

- Visualization: Uses mplfinance to plot candlesticks, EMAs, key levels, and trade markers for easy analysis.

---

## Purpose

This script is designed for traders and analysts to identify high-probability trade setups by combining technical indicators and market structure in a systematic way. It provides a clear framework for multi-timeframe analysis and visualizing key levels.

---

## Dependencies

- pandas

- numpy

- matplotlib

- mplfinance
