---
title: "Machine Learning for Trading Capstone: Random Forest Stock Trading Agent"
excerpt: "Random Forest classification algorithm implemented with Python, Pandas, and NumPy to predict, buy, sell, and hold
opportunities for stock market data. (From scratch; no Scikit-Learn)"
collection: portfolio
---

## Introduction
This paper focuses on using Machine Learning to predict stock price movements using Technical Indicators. It utilizes five indicators with a Random Forest (RF) model and a manual strategy. The study aims to predict whether a stock's price will rise or fall and trade accordingly.

## Indicators Utilized
Four of the indicators signal overbought/oversold conditions, while one indicates volatility. Python, NumPy, and Pandas are used to process indicators, and vectorization is applied for performance. Indicators have varying parameters between the manual strategy and RF.

## Strategy
The manual strategy, inspired by the RF model, uses majority signals for trade decisions. Different indicators influence the strategy. High volatility is a sell signal, low volatility is a buy signal, and other thresholds are considered.

## Performance
The manual strategy outperforms the benchmark on in-sample and out-of-sample data. However, out-of-sample results are affected by the different market conditions.

## Random Forest Model
A Random Forest model is used, employing a grid search to optimize hyperparameters. The model is trained with technical indicators and outcomes. The impact of market movement against the strategy's decisions affects performance.

## Experiment One
The RF model outperforms the manual strategy and benchmark on in-sample data but performs worse on out-of-sample data due to potential overfitting.

## Experiment Two
Increasing market impact reduces cumulative return and executed trades for the RF strategy. Further exploration of parameters and strategies may improve performance.

This study demonstrates the application of Machine Learning and Technical Indicators for predicting stock price movements and highlights the challenges of generalizing strategies across different market conditions.
