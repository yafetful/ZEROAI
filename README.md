# 0ai.ai
[web](https://0ai.ai) | [twitter](https://twitter.com/zeroai_official) | [telegram channel](https://t.me/ZEROAI_channel)

## Overview
Welcome to the 0ai.ai project! Our mission is to harness the power of artificial intelligence to predict cryptocurrency prices with unparalleled accuracy. This project is at the forefront of blending advanced machine learning techniques with financial forecasting.
![historical_results_comparison](example/historical_results_comparison.png)
## Core Technologies
### 1. Long Short-Term Memory (LSTM) Networks: 
These are a special kind of recurrent neural network (RNN) capable of learning long-term dependencies. In our project, LSTM is instrumental in understanding the time-series data of cryptocurrencies, allowing us to capture patterns over extended periods.

### 2. Neural Prophet:
This is a cutting-edge forecasting tool that combines components from ARIMA (AutoRegressive Integrated Moving Average) models, Recurrent Neural Networks, and additional regressors. It provides an excellent balance between model simplicity and forecasting power, particularly for seasonal trends.

### 3. Random Forests: 
An ensemble learning method known for its robustness and versatility. We use it to predict cryptocurrency prices by analyzing a multitude of decision trees and determining the average prediction from various models, thus increasing the accuracy.

## Methodology
The project operates in two main stages:

**Initial Prediction Models**: Each technology (LSTM, Neural Prophet, and Random Forest) independently predicts daily and hourly cryptocurrency prices. These models are fine-tuned through extensive testing and hyperparameter optimization.

**Meta-Modeling Using Machine Learning**: We then synthesize these individual predictions, comparing them with historical real-world data. The machine learning meta-model harmonizes these diverse predictions into a single, more accurate forecast.
![price_prediction](example/price_prediction.png)
## Current Performance
Our model has demonstrated significant success in predicting prices for cryptocurrencies with substantial historical data, such as Bitcoin and Ethereum.

## Contributing
We welcome contributions from data scientists, AI enthusiasts, and financial analysts. Your expertise can help us refine our models and explore new frontiers in AI-driven financial forecasting.
