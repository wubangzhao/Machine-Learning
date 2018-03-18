Sentiment Analysis - Understanding and Extracting Feelings from Data
An API lets you access an apps functionality from youe code
TextBlob is awesome for NLP tasks


twitter_sentiment
Twitter Sentiment Analysis Challenge for Learn Python for Data Science #2 by @Sirajology on Youtube

##Overview

This is the code for the Twitter Sentiment Analyzer challenge for 'Learn Python for Data Science #2' by @Sirajology on YouTube. The code uses the tweepy library to access the Twitter API and the TextBlob library to perform Sentiment Analysis on each Tweet. We'll be able to see how positive or negative each tweet is about whatever topic we choose.

##Dependencies

tweepy (http://www.tweepy.org/)
textblob (https://textblob.readthedocs.io/en/dev/)
Install missing dependencies using pip

##Usage

Once you have your dependencies installed via pip, run the script in terminal via

python demo.py
##Challenge

Instead of printing out each tweet, save each Tweet to a CSV file with an associated label. The label should be either 'Positive' or 'Negative'. You can define the sentiment polarity threshold yourself, whatever you think constitutes a tweet being positive/negative. 
