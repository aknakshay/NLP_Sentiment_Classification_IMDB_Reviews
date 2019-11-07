# NLP_Sentiment_Classification_IMDB_Reviews
Performing Sentiment Classification on IMDB Reviews using Deep Learning.

The task is to classify the sentiment of the text. 

## Cleaning
Set of Stop words is taken and the stop words which can have an impact on sentiment are removed from stop word set.
Text is cleaned by removing html tags, removing limited stop words, and performing case normalization. 

## Vocabulary Filteration
The data is further filtered by restricting the vocabulary size to 10000 of most common words.

## Encoding and Padding
Data is then encoded into numbers and padded to have the same length. 

## Model
A Bidirectional GRU model is trained over data with tanh activation. 
In two epochs only, model fits the data and gives an accuracy of around 87%.
