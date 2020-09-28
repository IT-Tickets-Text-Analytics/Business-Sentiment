# Business-Sentiment
We suggest a specific approach of Business Sentiment as an instrument for measuring the emotional component of an IT ticket. This latent information is extracted from the unstructured IT ticket texts with the help of a lexicon-based approach. As standard lexicons do not work well in our context of IT ticket classification, using the state-of-the-art VADER and LDA, we developed a domain specific lexicon. Each of the words is associated with positive, negative or neutral sentiment. In particular, words with valence score greater than 0 are considered to be positive, whereas words with valence score less than 0 are considered to be negative. All other words are considered to have neutral sentiment. For each IT ticket text, we determine the proportion of words with negative, neutral and positive sentiment together with intensifiers (exclamation marks, capitalizations and special characters).
3_Sentiment.py identifies the number and score of positive, negative and neutral words (according to the domain specific context aware Business Sentiment lexicon)
