# Deep-Learning-and-Machine-Learning-Models
This repository includes the code used for a Final Capstone Project at IE University. All rights reserved to the author.

Repository of the analsys for the Capstone Thesis "A Comparison: AI and Technical Analysis Bitcoin Trading Strategies"
Paper submitted to IE University by Tara Habsburg Lothringen.

Bitcoin is currently the cryptocurrency with the highest market capitalization and has experienced a massive growth of investor interest in recent years. However, its volatility is a significant challenge as it can be influenced by numerous sentimental, technical, and legal factors. Algorithmic trading is a popular way that tries to overcome these challenges. This paper compares the profitability of five individually optimised technical analysis strategies from the open-source trading system, Freqtrade, to several AI-empowered strategies, an LSTM deep learning model and an ARIMA machine learning model, a Lasso Regression Model and more. 

Data:
To achieve this objective, historical daily OHLC price data of the Bitcoin/ USD trading pair was obtained from a financial data provider and all strategies were back tested using that dataset. The dataset used can be found in this same repository under BTC/USD.csv.

Methodoogy:
Data preprocessing, Feature engineering and selection, Hyperparameter Tuning, Model Evaluation and Profit Calculation have been conducted.

Backtesting:
The methods were optimised, evaluated, and back tested on a 1000$ initial investment over the past two years for the time period from February 1st, 2021, up to February 1st, 2023 using profit as a metric for comparison. 

Resuts:
The results demonstrate that all seven strategies significantly outperformed the market, with the ARIMA Model Trading Strategy achieving the highest ablsoute profit of 35.88%, outperforming the market change of -58% by over 85%.
The LSTM Model achieved an accuracy of 55%.
The ARIMA Model achieved a (superficial) accuracy of 53%.
