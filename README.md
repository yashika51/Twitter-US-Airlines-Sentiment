# Twitter-US-Airlines-Sentiment
Analyze how travelers in February 2015 expressed their feelings on Twitter


This repository contains the analysis and classfication model for the dataset taken from Kaggle's [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment).

The dataset contains following columns:

- tweet_id: Tweet ID
- airline_sentiment: Sentiment of each Tweet (Positive, Neutral, Negative)
- airline_sentiment_confidence: Information not given
- negativereason: The reason of each negative comment
- negativereason_confidence: Information not given
- airline: The name of the airline company
- airline_sentiment_gold: Information not given
- name: The username of each Twitter account
- negativereason_gold: Information not given
- retweet_count: The number of re-posting of each Tweet
- text: The content of each Tweet
- tweet_coord: Information not given
- tweet_created: The exact time each tweet was posted
- tweet_location: Information not given
- user_timezone: The time zone that each user was in

The goal is to classify whether the sentiment of the text(present in the form of a tweet by someone) is **negative**, **neutral** or **positive**.

The repository contains two notebooks

- `Analysis.ipynb`: It contains the analysis, visulaizations and conclusions made by analysing the data.
- `Model.ipynb`: It cotains the complete model and the results acheived.

We have used transfer learning and ULMFiT to prepare our classification model. For more information about ULMFiT visit [here](http://nlp.fast.ai/).

