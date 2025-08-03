Developing a trading strategy using machine learning. \
A stacked ensemble model: \
LSTM_GRU hybrid + CNN_LSTM hybrid followed by an ANN error model.\
\
\
The models are trained on common trading indicators and continuous variables over random sequences of continuous trading days with the goal of predicting the price action over a forecast horizon. \
\
\
Binary and trinary features:\
'OBV_Indicator', 'Divergence', 'Trend_Confirmation', \
'MACD_Crossover', 'MACD_Divergence', '50_200_SMA_Cross', \
'12_26_EMA_Cross', '50_200_EMA_Cross', 'Trend_Strength',\
'MFI_Signal', 'Stochastic_Signal', 'All_volume_weighted_Signal',\
'RSI_ROC_Signal', 'CCI_Aroon_Signal'\
\
\
Continuous Features:\
'Open', 'High', 'Low', 'Close', 'Volume'
\
\
General order of the script:\
1) Retrieves stock historical data and appends several metrics and associated derivative indicators.\
2) Data is then preprocessed - train/test split, random sequence generation, normalization, etc..\
3) Base and error models are defined/trained\
4) The meta model is trained\
5) The fully trained meta model makes predicitons which are used for evaluation\
6) Evaluation visuals are created\
7) A trading strategy is developed using the meta model predicitons\
8) A backtest is performed and the performance of the trading algorithm is compared to buy and hold strategies\
9) Metrics for the trading algo are produced\
\
\
\
*Note: This model is NOT generalizable, and is only built for this application (trading SPXL)\
**The full script no longer functions as of 08/02/2025
