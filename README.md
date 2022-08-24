# SDIC 2022——PHAS0077: Scientific Computing Individual Research Project

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

This project could be divided into two parts: first part concentrate on training models for price prediction of the future market; second parts focuses on the investigations on the trading signals.

## Table of Contents

- [Price Prediction Model-Machine Learning](#machine-learning-price-prediction-model)
- [Price Prediction Model-Neural Network](#neural-network-price-prediction-model)
- [Trading Signals-Classical Indicator](#classical-indicator)
- [Trading Signals-Chart Analysis Signals](#chart-analysis-signals)
- [Input Data](#input-data)
- [Contributors](#contributors)
- [License](#license)

# Price Prediction Model

This experiment includes two sub-tasks. First is to training the price prediction models with the common seen machine learning models, and the second aims to consturct more complex neural network.

## Machine Learning Price Prediction Model
This experiment describes an in-depth exploration of the application of the classical machine learning model in the asset/stock price prediction system. The study reviews the characteristics and the features of the dataset and accordingly selects a few models including the linear and tree models which are expected to perform well in our case. The techniques in model optimisations including feature engineering and hyper-parameter tunning are also presented. 

## Neural Network Price Prediction Model
This chapter presents the investigation of the application of the neural network model in the asset/stock price prediction system. The study reviews the few neural network structure and tests their performances. The data also has been transformed into high dimensional time series data referring to the previous work in time series prediction in other industries. The models are optimised by adjusting the network structure and optimisers. The performance is evaluated by determining the root mean square error.

# Trading Signals
This experiment includes two sub-tasks. The first task verify the effectiveness of some classical signals in current the crude oil market. The second task attempt to convert four patterns in chart analysis into signals and test their performance.  

## Classical Indicator
The first task reviews the popular signals introduced in the past few decades. Some of them are modified to fit the current market, and an in-depth examination of their performance in aiding trading timing is then carried out. 
The indicators used/modified are MACD, RSI, Bollinger Band and KDJ.

## Chart Analysis Signals
The second task concentrates on the extraction of the signals from the technical chart analysis, such as the signals reflecting the falling edge patterns. The signals are wrapped into the trading strategies and their effects on the trading timing are evaluated. 

## Input Data

The data used in the notebooks are as follows:
- Crude Oil WTI Futures Historical Data (Crude Oil WTI Futures Historical Data.csv)
- Federal Funds Composite Interest Rate Historical Data-Daily (Federal Funds Composite Interest Rate Historical Data-Daily.csv)

## Contributors

This projects exists thanks to supervisors Prof Philip Treleaven and Dr Wilbur Zhu for their patience and willingness to help  throughout the project, from the detailed guidance to such much advice on the development of thesis and code. 

## License

[MIT](LICENSE) © tz1003
