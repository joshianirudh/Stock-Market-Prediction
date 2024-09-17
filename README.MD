# Time-Series-Forecasting-and-Analysis-of-Reliance-Stocks

Predicting stock prices using Time series forecasting techniques like:  [SMA](https://www.investopedia.com/terms/s/sma.asp) (Simple Moving Average), [EMA](https://www.investopedia.com/terms/e/ema.asp) (Exponential Moving Average), [MOM](https://www.investopedia.com/terms/m/momentum.asp) (Momentum), [RSI](https://www.investopedia.com/terms/r/rsi.asp) (Relative Strength Index), [MACD](https://www.investopedia.com/terms/m/macd.asp) (Moving Average Convergence Divergence).

And ML Algorithms such as: Linear Regression, Decision Trees, RandomForest, XGBoost.

## Requirments

NSEPY library 
TA-LIB Library

Run these commands to set-up  TIP: Works on colab easily
```python
!wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz 
!tar -xzvf ta-lib-0.4.0-src.tar.gz
%cd ta-lib
!./configure --prefix=/usr
!make                                                                                                                                                                     !make install
!pip install Ta-Lib
!pip install nsepy
```
LEARN how to use NSEPY: [here](https://nsepy.xyz/)
