# Stock-Predictions
Predicting stock prices is one of the hottest topics in the Financial market.
And the most interesting point of all these predictions and forecasting are none of them are accurate. 

Stock prices are unpredictable because of that its being difficult to predict using ML.
I Used NSEapi for fetching Stock Data for Indian Stocks and ARIMA model for stock Predictions 

By doing some Research and refered some Research paper i thaught that for predicting Stock accurately we must know about News and Investor Sentiment
So, I used Twitter Sentiment Analysis for Public Sentiment for the Company 
And News Sentiment Analysis for Checking the News Sentiments 
(There are some Other factors that Effects Stock prices too but for this Project Im focusing only on Sentiments)

Problem I faced that Tweepy Don't Gives us tweets more than 200 and only 7 days old tweets 
and for NewsApi i can fetch only 100 news headlines 
So , i Fetched only 1 Week data and done Sentiment Analysis on them.

I used INFY Stock prices:
From 25/2/2020 to 3/3/2020,The Sentiment of Tweets and News for INFY didnt have any effects on the stock prices because the Market was bearish because of Corona Virus so, Fetched Sensex Tweets and Sensex News Sentiment and can see some Relationship But for 1 week data it was difficult to come across some Pattern. 

Im just a Beginner in Machine Learning 

Future works:
1) By fetching 1 month sentiment can get some more relationship and can implement some Functions to Improve Accuracy.
2) Sentiment Analysis of News And Twitter can be Improved by hyperparameter tuning.
3) By selecting Important News and Tweets will help a lot in this project.

Thank you,

