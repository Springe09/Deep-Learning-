# Deep-Learning

# LSTM Stock Predictor


Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

You will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

You will need to:

1. Prepare the data for training and testing

* The model will use a rolling 10 day window to predict the 11th day closing price.
* Use the window_data function to generate the X and y values for the model.
* Split the data into 70% training and 30% testing
* Apply the MinMaxScaler to the X and y values
* Reshape the X_train and X_test data for the model.

3. Build and train custom LSTM RNNs

* Define the model architecture
* Compile the model
* Fit the model to the training data

5. Evaluate the performance of each model

* Which model has a lower loss?\
  The closing price model has a lower loss.

* Which model tracks the actual values better over time?

* Which window size works best for the model?



