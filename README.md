# Twitter-Sentiment-Analysis
# Brief Introduction

Objective of this project was to train a classifier which can take a tweets as input and give output user sentiment whether it is positive or negative

This project involved fetching live tweets of a user and then performing various analysis, cleaning that data and then training the classifier which can then be used to analyze the sentiment of those tweets or in general any text data.

NLTK, Tweepy, Textblob, Wordcloud, Scikit-Learn libraries were extensively used.


# Details about the project

Steps to be performed:

1.) Creating a twitter developer account and creating a twitter app to get required tokens and keys
2.) Authentication of credentials
3.) Fetching tweets from twitter
4.) Fetching important attributes from tweets
5.) Saving the attributes in the dataframe
6.) Dataframe of Tweets' attributes
7.) Removing twitter handles
8.) Removing punctuation number and special characters
9.) Tokenizing and removing stop words
10.) Re-join and apply lemmatization
11.) Checking sentiment using TextBlob
12.) Analysing sentiment using NaiveBayes Analyzer
