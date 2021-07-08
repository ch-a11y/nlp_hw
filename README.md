# cryptocurrency sentiment analysis

In this assignment, I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I also applied fundamental NLP techniques to understand other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

I completed the following tasks:

1. Sentiment Analysis;
2. Natural Language Processing;
3. Named Entity Recognition.


### 1 - Sentiment Analysis

> Ethereum had the highest mean positive score
>
> Bitcoin had a higher negative score by .01 to Ethereum
>
> Ethereum had the highest positive score and the highest compound score

### 2 - Natural Language Processing

In this section, I used NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. 

#### Tokenize

1. Lowercase each word;
2. Remove punctuation;
3. Remove stop words.

#### N-grams

I used ngrams to analys the words frequency for each coin.

1. Used NLTK to produce the ngrams for N = 2.
2. Listed the top 10 words for each coin.
