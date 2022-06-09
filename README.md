# Capstone_Project_Group_B - Algorithmic Trading
Prepared by:  Jacky Hong, Paaras Dhaliwal, Shavan Patel and Luke Evans. 

![[head.jpg]](images/head.jpg)

## Overview
This project evaluates different technical analysis trading strategies through quantitative testing to understand if we can add value compared to random. A work in progress with an end goal to create and implement a rule-based trading strategy using a scientific approach.

## Usage
To create a framework and method to approach quantitative testing on various financial assets. This allows you to quantify the results, validate performance, help with cognitive biases, and know your signals to assist with position sizing and management.

## Process
* Idea generation
* Code the rules
* Visually inspect the chart entry and exits to look for logic errors
* Backtest


## Installs used
* yfinance 
* numpy
* pandas
* hvplot
* finta
* talib
* quantsats

## Results

### ADX and SAR sy=trategy 


![[adx_sar_metrics]](images/adx_sar_metrics.png)


![[adx_sar_metrics_2]](images/adx_sar_metrics_2.png)


![[adx_sar_summary]](images/adx_sar_summary.PNG)


### Ichimoku Cloud and RSI strategy

![[ichimoku_benchmark_vol]](images/ichimoku_benchmark_volatility.png)


![[ichi_drawdowns]](images/ichi_underwater.png)


### Channel Breakout Strategy

![[channel_BO]](images/channel_bo.png)

### Forex Strategy

![[FX]](images/forex.png)



## Improvements
Build a testing framework template to utilise across all instruments and attempt to eliminate market trends (positive returns from the signal, not from the general market moves) and path dependency from optimization.

---





