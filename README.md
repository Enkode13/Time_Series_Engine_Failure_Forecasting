# Time_Series_Engine_Failure_Forecasting
This project is about predicting/forecasting the number of time cycles remaining to engine failure. 
Two models were used.
One of them is a simple RNN model and the other one is an LSTM model.
Tensorflow and keras was used to implement the above said models.
Features were selected based on the correlation matrix. 
The ones with correlations higher than 0.5 to the target variable were selected.
Preprocessing was done on the data to standardize and reshape it to fit the models.
