# Sentiment-Classification-of-IMDB-Movie-reviews-using-Bert:

IMDB dataset having 50K movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification
## Source of data: https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

I have used pretrained DistilBert model to extract the text features from IMDB movie reviews to classify the sentiment(Positive or Negative) of the movie review text.
After extracting the trained and test features from IMDB movie reviews , i trained the Fully connected neural network to classify the text, i have used sigmoid activation at the output layer which gives the probability score of text being positive.
