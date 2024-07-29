---
title: "Tesla Stock Price Predictor"
excerpt: " A machine learning-powered tool predicting Tesla stock prices using real-time Twitter sentiment analysis.
<br/><img src=\"../images/tesla.png\" style=\"display: block; margin-left: auto; margin-right: auto; width: 50%;\"/>"
collection: projects
---
Desrciption:

This forecasted Tesla's stock price by leveraging Twitter sentiment analysis and an LSTM Model. By collecting and analyzing tweets related to Tesla using a pre-trained BERT model for sentiment classification, it calculated sentiment scores that, along with other financial indicators, were fed into a Long Short-Term Memory (LSTM) neural network.

The LSTM model, was configured with two layers of 50 units each, a dropout rate of 0.2, and trained with the Adam optimizer. The model processed features such as historical stock prices, trading volume, and sentiment scores over a 30-day sequence length. Hyperparameters like batch size, sequence length, and learning rate were fine-tuned to ensure the model's accuracy and prevent overfitting.

Built entirely in Python, the project utilized TensorFlow for the LSTM model, Scikit-learn for data preprocessing and evaluation, and Tweepy for Twitter API integration. 