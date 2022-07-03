# Sentiment-Analysis

The goal of the project is to build two different machine learning models for sentiment analysis on the given dataset. The dataset is the Sentiment140 dataset, a publicly available data set created by three graduate students at Stanford University: Alec Go, Richa Bhayani, and Lei Huang. The two models built are to be compared to see which one performs better.


In the project, two different machine learning models were explored: convolutional neural network (CNN) and a bidirectional LSTM. After hyper-parameter tuning, the Convolutional Neural Network model gave an accuracy of 75.24%. The Bidirectional LSTM model gave accuracy of 76.07% with a precision, recall, and f1-score of 0.77, 0.75, and 0.76 respectively too for 0, and 0.75, 0.77, and 0.76 for 1. The bidirectional LSTM performed better than the CNN because it made the predictions based on data sequences, unlike the CNN which uses spatial correlation in the data. The CNN usually works better on images.
