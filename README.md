# Predicting the Decade by Song Lyrics

I found a dataset from [Kaggle](https://www.kaggle.com/rakannimer/billboard-lyrics) that contains the song title, artist, song lyrics, and year a song was produced. From this dataset, I wanted to see if song lyrics could predict what decade a song was produced.

Initially I performed exploratory data analysis on the data and found some of the song lyrics were missing in the dataset. I decided it was best to drop the missing samples since it was only 3.6% of the data.

Then I vectorized the lyrics to see what the top 2-word phrases of the lyrics were. I was not surprised to find that most of the phrases were filler words in songs such as oh oh and yeah yeah.

Next I modeled my data on four different kinds of models, Logistic Regression, Random Forest, Bagging Classifier, and AdaBooster Classifier, and I found that the Logistic Regression model performed the best.

The baseline score for predicting accuracy was 20%, and the Logistic Regression model was able to get a 38% accuracy score.

I also decided to try and create a model off of the song titles, but after training and testing the same model types as I did for the lyrics. I found that lyrics are better at predicting.
