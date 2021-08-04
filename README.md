Stock Price Prediction Using Machine Learning

Brief:
Design of a deep learning model using Long Short-Term
Memory networks that will be able to predict future stock prices after it has been
trained and tested on pre-processed data available on Yahoo Finance.

Objectives:
The main objective of this work is to find a solution for predicting the closing price
of a company share with a day or more in the future having a pleasant accuracy.
The prediction will be based on historical closing prices of the company, the preprocessed data set that being split into training and testing sets, 80% for training and
the rest for testing. The neural network with LSTM, Dropout and Dense layers will be
trained and the results will be validated on the test set. Also, EarlyStopping callbacks
will be used to prevent overtraining of the model. Basically, this will stop the model
training when the loss is not improving.
The trained model will try to make predictions in the future, coming up with a
future closing price of the share. Being based on previous prices, the accuracy might turn
out high but that will be analyzed and explained further later in the paper.
Predictions will be plotted and analyzed accordingly, and the model performance
will be highlighted.
