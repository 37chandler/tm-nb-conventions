# Naive Bayes Assignment

In this assignment we use Naive Bayes (NB) for its two greatest strengths: 
1. Exploration of a data set 
1. Classification of new data based on training data

The databases are not small, so I've put them on Canvas. When you download those files move them into the repository folder. 

## Part 1: Exploratory Naive Bayes

In this section, you will build a Naïve Bayes classifier on the convention speeches of 2024, using the words of the speech text to predict the party (either Republican or Democratic). Your starting notebook walks you through the steps of fitting and using a Naïve Bayes model from the NLTK package. This repo includes some code that would help you limit the number of words you consider in your model, which might improve run-time. We have asked you to fill in some observations from the fitted model.

## Part 2: Classifying Tweets

We have a pretty gigantic database of tweets (and other data) from 
everyone running for Congress in 2018. As an exercise, we'll try to 
use this convention model to classify those tweets. 

The notebook walks you through the steps in broad terms: 
1. Pull data from the congressional DB.
1. Clean, tokenize, and build your feature dictionary for a tweet.
1. Use the classifier from Part 1 to estimate the party of the tweeter.
1. Compare this estimate to their actual party.

If you're looking to go further on the assignment, consider building a model based on 2024 data, 2020 data, and 2016 data. Which one has the best predictive accuracy? My instinct is that 2016 will, but I haven't tested it. 


