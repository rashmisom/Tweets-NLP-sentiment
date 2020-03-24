Real or Not? NLP with Disaster Tweets
Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).
In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.
The Dataset
We have access to a dataset of 10,000 tweets that were hand classified.
We are predicting whether a given tweet is about a real disaster or not.
If so, predict a 1. If not, predict a 0.
The Files we are dealing with are: train.csv - the training set test.csv - the test set
The features involved are: id - a unique identifier for each tweet text - the text of the tweet location - the location the tweet was sent from (may be blank) keyword - a particular keyword from the tweet (may be blank) target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)