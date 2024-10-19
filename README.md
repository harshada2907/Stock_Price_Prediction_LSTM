# Stock_Price_Prediction_LSTM


# keras and TensorFlow > 2.0

# Steps:
#1. We will collect the Stock Data -- AAPL- ticker symbol for Apple Inc
#2. Preprocess the Data - Train and Test
#3. Create a stacked LSTM Model
#4. Predict the test data and plot the output
#5. Predict the future 30 days and plot the output

120, 130, 125, 140, 134, 150 ||||| 160, 190, 154

different train and test split methods
Cross Validation 
random seed
but these are suitable for linear regression and classification

Timeseries data --> Train- 120, 130, 125, 140, 134, 150   Test - 160, 190, 154


120, 130, 125, 140, 134, 150                             160, 190, 154, 160, 170

Timesteps=3 - on how many previous days will the next day output depend upon

For training data:-

   X_train      y_train
f1   f2   f3     o/p
120  130  125    140
130  125  140    134  --> shifting 1 position to the right


For testing data:-

   X_test       y_test
f1   f2   f3     o/p
160  190  154    160
190  154  160    170



