# US-Election-Prediction-2020

##SentimentAnalysis.ipynb
The file SentimentAnalysis.ipynb contains the code for carrying out the analysis.
The file imports data from the drive to make the process of adding data to the colab a lot easier.
The file contains code for running predictions on 2 types of data
1) IEEE dataset which contain more than 24 million tweets with sentiment analysis already applied on the data
2) Personally fetched data using the streaming API from twitter and carrying out sentiment analysis using textblob

The IEEE dataset doesn't contain location based information thus is used to only carry out a national estimate.
The personally fetched data is manipulated to calculate a statewise percentage.

##twitter_data.ipynb
This file contains code to use the tweepy streaming api to collect data from twitter for our analysis.
The access tokens need to be filled out before running the code.
The search filters are specific to the 2020 US elections and can be modified if used for other purposes
The data collected is exported as a csv file to be used for further manipulation
