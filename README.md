# Backtesting Engine
## Overview
This repository is designed to offer a comprehensive suite of Jupyter notebooks for backtesting financial trading strategies by simulating their performance on historical data. There are several versions of the backtesting engine with different approaches, allowing to explore everything from basic single-stock analyses to advanced portfolio strategies.

## Contents
 - *Simple Backtesting.ipynb*: Offers a beginner-friendly approach focusing on straightforward trading strategies for single stocks.
 - *Backtesting Engine v0.ipynb*: Introduces fundamental backtesting capabilities with the use of capital limitations.
 - *Backtesting Engine v1.ipynb*: Enhances the basic model by adding concepts such as trading signal strength and leverage, i.e. borrowing money to invest it.
 - *Backtesting Engine v2.ipynb*: Expands to multiple stock analysis, refining data handling and integrating complex strategy testing across a diversified portfolio.
 - *MACD Backtest.ipynb*: Implements the MACD indicator for technical analysis to generate trading signals, and applys the backtesting engine to test its performance over 2 years.

## Example
![Results MACD](https://github.com/AndresMireles/BacktestingEngine/assets/64489886/4c2013c0-b8e7-44d5-a1ce-61075a59b182)

## Getting Started
1. Clone or download this repository to your local system.
2. Install Jupyter Notebook or Jupyter Lab to interact with the notebooks.
3. Ensure all dependencies are installed:
   *pip install pandas numpy yfinance pandas_datareader talib*
4. Select the version of the engine that most fits your needs, select a time range and the stock(s) to backtest.
