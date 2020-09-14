# Stock-Analysis-Prediction_Python

### Objectives
Stock market trading is one of the most interesting but risky investment measures studied by various professionals. According to some estimates, only 20% of professionals are good investors and the other 80% perform worse than the average broad stock market or even negatively. For people without financial and market knowledge, investing in the stock market is as risky as pure gambling. In this project, we aim to assist individual investors as well as professionals such as fund managers in investment management. Based on selected technical indicators, we recommend the best model to predict three target variables: logarithm of return, price moving direction, and asset return.

### Source
Yahoo Finance API
```
install yfinance
import yfinance as yf
stock_df=yf.download("PFE",start="2010-01-01",end="2019-12-31")
```

### Structure
* Predictive model training: Linear, Machine Learning, Deep Learning
* Trade simulation:Basing on Momentum, RSI signal, Candlestick Chart and Bollinger Bands.
* Model comparison and trade signal selection


### Tools:
Python, Jupyter Notebook

### References: https://www.nowcoder.com/tutorial/10015/index
