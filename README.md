# udacity_data_wrangling
Using python to download data programmatically, from web pages and API, with basic natural language processing to analyse tweet sentiments from a sample of tweets on Twitter. Cleaning the data ready for use in analysis.

## Dataset

> The data in this dataset contains tweets from the WeRateDogs twitter account, which rates dogs out of 10 based on picture of them submitted by their humans. The data is gathered using Twitter's API with the tweepy library. Photos were also downloaded using the PIL library and twitter api data was downloaded and saved as a json file before being read into the jupyter notebook.
libraries used:
pandas
numpy
requests
os
tweepy
json
PIL
io
collections
nltk

## Summary of Findings

> The number of likes for each tweet was proportional to the number of retweets. Sentiment analysis was also created using basic natural language processing with the nltk and collections libraries. Tweets with strong sentiment had the highest median rating from WeRateDogs, but overall, tweets with medium or low sentiment had higher maximum ratings than the strong sentiment tweets. 'Puppo' dogs were the best rated on average. Golden retrievers were the most common dog.
