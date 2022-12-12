# 510_Project

This project utilizes historical 30-minute candlestick data on SPY from May 5th, 2008 to November 2nd, 2022 downloaded from Barchart.com.
The original dataset is used to craft a second dataset of the slopes between local extrema of the EMA3 on the SPY closing price for each candle.
The second dataset is utilized to train and test logistic regression models for predicting the next slope from Local Minimum to Local Minimum,
and predicting the next slope from Local Maximum to Local Maximum.
Those models are then deployed on a backtest of the original dataset, the historical 30-minute candlestick data on SPY.
All code and plots are my own original work.
