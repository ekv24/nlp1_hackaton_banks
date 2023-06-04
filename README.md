# NLP1 Hackathon: Bank Review Classification and Clustering

Welcome to the NLP1 Hackathon: Bank Review Classification and Clustering project! 🏦🔍

## Description

In this competition, our team created an algorithm that can classify bank reviews and clusterize them by meanings.

### Features

We developed a variety of features to capture different aspects of the bank reviews, including:

- Number of exclamation marks
- Answer signs
- Presence of phone number in the review
- Names of banks
- Length of the review
- Presence of a date
- Number of capital letters
- etc.
### Sentiment Analysis

To analyze the mood of the reviews, we utilized various techniques:

- We created local bags of bad/good words to identify positive and negative sentiments.
- One of our features was the difference between the count of close and open brackets, which helped capture the sentiment of the review.
- We leveraged the "nltk" library to analyze the mood of the reviews using natural language processing techniques.

### Algorithm Training and Predictions

Using these features, we trained a Random Forest algorithm for classification and clustering tasks. The algorithm learned from the provided labeled data and made predictions on unseen bank reviews.
