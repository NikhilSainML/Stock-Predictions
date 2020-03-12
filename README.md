# Stock-Predictions
Predicting stock prices is one of the hottest topics in the Financial market.
And the most interesting point of all these predictions and forecasting are none of them are accurate. 

Stock prices are unpredictable because that its being difficult to predict using ML.
I Used NSEapi for fetching Stock Data for Indian Stocks 
In this project I used ARIMA model for stock Predictions 

In this project i have done some Research and came accross that for predicting Stock accurately we must know about News and Investor Sentiment
So, I used Twitter Sentiment Analysis for Public Sentiment for the Company 
And News Sentiment Analysis for Checking the News Sentiments 
(There are some Other factors that Effects Stock prices but for this Project Im focusing only on Sentiments)

Problem I faced that Tweepy Don't Gives us tweets more than 200 and only 7 days old tweets 
and for NewsApi i can fetch only 100 news headlines 
So , i just implement only 1 Week Sentiment data
I used INFY Stock prices:
From 25/2/2020 to 3/3/2020,The Sentiment of Tweets and News for INFY didnt have any effects on the stock prices because the Market was bearish because of Corona Virus so, Fetched Sensex Tweets and News Sentiment and can see a Relationship But for 1 week data it was difficult to come across a relationship. 

Im just a Beginner in Machine Learning 

Future works:
By fetching 1 month sentiment can get some more relationship and can implement some Functions to Improve Accuracy

Thank you,

