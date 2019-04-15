# TimeSeriesTensorflow
Some basic forecasting scripts using the Tensorflow library
Examples of forecasting using Tensorflow's time series api and LSTM. 
This code was taken from Google repositories and then modified so as to be applied to real world data sets (e.g. the Air Paseengers data set from Box and Jenkins). 

Models used: 
ARRegressor, which is a feed forward neural network as a non linear AR model, similar in spirit to Rob Hyndman's NNETAR function in R's Forecast package. 
State Space Regressor, which creates a structural model similar to the BSTS model proposed by Scott and Varan. 
LSTM, which are recurrent neural networks using LSTM gates instead of regular activation functions.  
