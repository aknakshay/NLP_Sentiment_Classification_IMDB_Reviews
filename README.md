# NLP_Sentiment_Classification_IMDB_Reviews
Performing Sentiment Classification on IMDB Reviews using Deep Learning.

The task is to classify the sentiment of the text. Text is first cleaned by removing html tags, removing limited stop words, and performing case normalization. The data is further filtered by restricting the vocabulary size.


Data is then encoded into numbers and padded to have the same length. A Bidirectional GRU model is trained over data with tanh activation. In two epochs only, model fits the data and gives an accuracy of around 87%.
