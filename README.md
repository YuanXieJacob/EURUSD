# EURUSD Currency Trading Experiment

This project is for fun! And profit, if any.

The goal of this project is :

1. Develope an alpha model predicting Forex Movements (with accurary >= 70%);
2. Integrate it with a Algo Trading Enginne;
3. Add on Risk Management Modules to control drawdowns (e.g. Position Sizer & Emergency Stopper);

EURUSD 5-minute price data is from Dukascopy.com using their historical data feed. 

## Current Achievements:

* Lots of price-based features added;
* Used GDBT for benchmark prediction (no feature selection & parameters adjustments), got accuracy score of 0.6690;
* A simple backtest example using Backtrader(an Open Source framework for backtest & live trading);

## Working on:

### Alpha Model:

* Deep Neural Network model prediction (classification);
* Change from a classification to a regression model to produce a profit target or a signal strength indicator;
* Integrate model with Backtrader framework;

### Algo Trading Implementation:
 
* Add leverage/margin/commission setting;
* Add position sizer;
