# Twitter_Sentiment_Analysis_US_Presedential_Elction2020

**Objective: Using Python Script Extraction of tweets and Perform sentiment analysis on the presidential candidature of Donald Trump, Joe Biden before the elections in US in November, 2020.**
In this analysis extraction of tweets using Twitter's API, and GetOldTweets library to overcome the timeframe limitations of Twitter API is done. After extraction, I have done preprocessing for cleaning the datasets, basic EDA, sentiment analysis to observe polarity towards each candidate, used classification models on these sentiments and created visualizations.

**Data Preprocessing :** 
Data Preprocessing is a very crusial part for this project.Data preprocessing is the process of transforming raw data into a useful, understandable format.By preprocessing data, we make it easier to interpret and use. This process eliminates inconsistencies or duplicates in data, which can otherwise negatively affect a model’s accuracy. Data preprocessing also ensures that there aren’t any incorrect or missing values due to human error or bugs. In short, employing data preprocessing techniques makes the database more complete and accurate.
Steps to process the twitter data :

* Using Regular Expressions to remove Emojis from Tweets

* Using Regular Expressions to remove any retweets (if they exist)

* Using Regular Expressions to remove the usernames from the tweets as they do not provide any additional information

* Using Regular Expressions to remove any URLs, websites,etc

* Using Regular Expressions to identify for any hashtags in the tweet, & if they exist, remove the hashtag & keep the word. This can be very useful when modelling as it does not remove any possible words that might be a major factor in calculating the sentiment

* Using Regular Expressions to remove any special characters, numbers , punctuations

* Converting everything to lower case

* Lastly, used the Tweet-Preprocessor Module for cleaning any leftover junk.

Above portion is the main preprocessing part.Now for calculating sentiment perform certain task using NLTK module.Steps are given below:

* NLTK Module used to tokenize all words

* NLTK Module used for removing any existing stop words (eg. Or , from , them, Does , etc)

* NLTK Module used to perform stemming

* Words that less than a length of 2 were dropped

**Sentiment Analysis : **

Sentiment analysis is used to analyze raw text to drive objective quantitative results using natural language processing, machine learning, and other data analytics techniques. It is used to detect positive or negative sentiment in text, and often businesses use it to gauge branded reputation among their customers. 
Lexicon file is used to calculate the sentiment of each tweets.

