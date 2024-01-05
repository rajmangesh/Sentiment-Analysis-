# Sentiment-Analysis-


The Project explores sentiment analysis on Amazon reviews data. It first loads a sample of 500 reviews into a Pandas dataframe. Some exploratory data analysis is done by plotting the distribution of review scores and examining some sample reviews.

Two sentiment analysis techniques are then applied:

- **Vader** - This is a lexicon-based sentiment analysis tool that looks at words and phrases in the text and assigns 
              sentiment scores for positive, negative, and neutral sentiment. It calculates an overall "compound" sentiment 
              score.
- **Roberta** - This is a transformer model fine-tuned for sentiment analysis. It is used to predict the probability of a 
                positive, negative or neutral sentiment for each review.
  
The Vader and RoBERTA sentiment scores are calculated for each review and added to the dataframe. This allows comparing the scores between the two techniques.

Some sample reviews are examined that have mismatching sentiment scores between the star rating and model predictions. This highlights that star ratings don't always align with sentiment.

The Transformer pipeline is also demoed to show an easier way to apply a sentiment analysis model, without having to load and tokenize a model yourself.

Overall, this Project provides a nice walkthrough of applying sentiment analysis on text data, comparing lexicon-based and transformer approaches, and some of the analysis you can do with sentiment scores. 
