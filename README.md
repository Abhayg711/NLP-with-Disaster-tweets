# NLP-with-Disaster-tweets


## Competition Description
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster.

The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified. If this is your first time working on an NLP problem, we've created a quick tutorial to get you up and running.

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

## Approach
In this notebook I have tried to implement techniques related to Natural Language processing (NLP). Steps involved:-
1) Extract information from the existing tweets - Number of hashtags, Number of captital words
2) Converting abbreviations to complete words
3) Data Cleaning - removing punctuation marks, removing stopwords, removing numbers
4) Lemmatization
5) Count Vectorizer
6) MultinomialNB & NN
