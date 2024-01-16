# Amazon-Reviews-Sentiment-Analysis
Using Transformer models to Classify Amazon Reviews into Positive, Negative of Neutral Sentiment

In this project we will be doing some sentiment analysis in python for Amazon Food product reviews using two different techniques:

* VADER(Valence Aware Dictionary and Sentiment Reasoner) - Bag of Words Approach
* Roberta Pretrained Model from Huggingface Pipeline

## About Database
This dataset consists of reviews of fine foods from Amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

<dataset_image>(https://github.com/chitransh1998/Amazon-Reviews-Sentiment-Analysis/blob/main/Dataset.png?raw=true)
### Contents
* Reviews.csv: Pulled from the corresponding SQLite table named Reviews in database.sqlite.
* database.sqlite: Contains the table Reviews.

### Data includes:
* Reviews from Oct 1999 - Oct 2012.
* 568,454 reviews.
* 256,059 users.
* 74,258 products.
* 260 users with more than 50 reviews.h > 50 reviews
