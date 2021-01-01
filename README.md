# US-Election-Prediction-2020

The file SentimentAnalysis.ipynb contains the code for carrying out the analysis.
The file imports data from the drive to make the process of adding data to the colab a lot easier.
The file contains code for running predictions on 2 types of data
1) IEEE dataset which contain more than 24 million tweets with sentiment analysis already applied on the data
2) Personally fetched data using the streaming API from twitter and carrying out sentiment analysis using textblob

The IEEE dataset doesn't contain location based information thus is used to only carry out a national estimate.
The personally fetched data is manipulated to calculate a statewise percentage.

