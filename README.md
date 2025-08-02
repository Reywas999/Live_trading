Developing a trading strategy using machine learning. \
A stacked ensemble model: \
LSTM_GRU hybrid + CNN_LSTM hybrid followed by an ANN error model.\
The models are trained on common trading indicators and continuous variables over random sequences of continuous trading days with the goal of predicting the price action over a forecast horizon. \
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
