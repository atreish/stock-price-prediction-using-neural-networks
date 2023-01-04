# stock-price-prediction-using-neural-networks

In this project we aim to predict the daily price of stocks for various publicly traded companies.

We employ a fully-connected feedforward neural network that uses 3 historical data values as inputs : the minimum price seen, maximum price seen, and average closing price across a 'sliding window' of time preceding the day that is to be predicted for.

The end-of-trading-day stock prices for the entirety of the years 2012 through 2019 (inclusive) are used as training data. The prices from the start of 2020 to the present (May 2021) are used as unseen testing data.

We create our network and then compare its performance across a variety of alterations: different activation function choices, different values for network parameters, and different lengths of time window for our inputs.

Finally, we run a small trading simulation using our test data to see whether our neural network predictions would be useful for generating revenue.
