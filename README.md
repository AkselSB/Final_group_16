# Final_group_16

For this exam project, we have made a repository with the necessary notebooks to scrape tweets with corona and danish politics related twitter posts

We use the following packages ...

**SCRAPING & CLEANING**: 
In the notebook called Scraping & Cleaning we use a Twitter developer API and the tweepy library to scrape tweets based on the hashtags: 
Covid19dk, coronadk, COVID19, DeltaVariant
dkpol, dkmedier, dkmedie

In order to be able to run this file you need a twitter developer API to get personal Twitter credentials:
consumer_key = "xxxxxxxxxxxxxxxx"
consumer_secret = "xxxxxxxxxxxxxxxx"
access_token = "xxxxxxxxxxxxxxxx"
access_token_secret = "xxxxxxxxxxxxxxxx"

We gained access via this link: https://developer.twitter.com/en/docs/twitter-api 

We further remove columns with unnecessary information about location, username etc.
we cleaned df1, df2 and df3 as well as dkpol_final the dataset we created in the scraping part. 

**SENTIMENT ANALYSIS**
In the notebook called Sentiment Analysis we made the analysis of the tweets based on the cleaned data called covid_tweets, our infection rate called positives and dkpol_final. 

