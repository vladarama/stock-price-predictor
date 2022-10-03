# stock-price-prediction

This team research project was done as a part of the Introduction to Computer Programming course at Dawson College.

### Introduction

Research question: How accurately can machine learning predict the closing price of a stock(dependent variable), based on the last x prices (independent variable), by measuring the impact of reduced interval of training on the percent error of our output.

Explanation: Nowadays, stock trading using bots and python is a very hot topic, since many think that it might be a profitable way to trade and to minimize risk. However, trading isn't as simple as everyone makes it to be; creating a bot to accurately and reliably predict the fluctuation of market prices isn't something simple. If that were the case, everyone would already be rich through stock trading. One of the reasons why trading is so difficult is because there are multiple factors that influence the fluctuation of the stocks' values such as news, market movements, the state of our economy, the emotions of traders, etc. People have taken advantage of these factors to create techniques for the purpose of helping to make decisions in the stock market, such as using existing data to predict future movements. However, as mentionned previously, it is not easy to do so reliably and accurately. As such, we want to see how accurately machine learning can predict the closing price of a stock, based on the last x number of prices, by measuring the impact of reduced training time on the percent error of our output.

### What I learned 
• How to retrieve stock information using Yahoo’s yfinance and how to prepare the data using Pandas and Sci-kit Learn

• How to implement a LSTM Neural Network from the Keras library and achieve a high accuracy by optimizing it's parameters

• How to measure the impact of reduced training interval on the percent error of our predictions by plotting various graphs and tables using Seaborn and Matplotlib
