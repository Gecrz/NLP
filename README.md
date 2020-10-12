# NLP

![Stock Sentiment](Images/sentimental.jpeg)

The goal is to apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. We will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

The goal is to Complete the following tasks:

1. [Sentiment Analysis](#Sentiment-Analysis)
2. [Natural Language Processing](#Natural-Language-Processing)
3. [Named Entity Recognition](#Named-Entity-Recognition)


#### Sentiment Analysis

Use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

#### Natural Language Processing

In this section, you will use NLTK and Python to tokenize the text for each coin. Be sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, look at the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

Finally, generate word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc-word-cloud.png)

![eth-word-cloud.png](Images/eth-word-cloud.png)

#### Named Entity Recognition

In this section, we will build a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](Images/btc-ner.png)

![eth-ner.png](Images/eth-ner.png)

These are the answers of the questions:

### Questions:

Q: Which coin had the highest mean positive score?

A: Bitcoin

Q: Which coin had the highest compound score?

A: Bitcoin

Q. Which coin had the highest positive score?

A: Bitcoin

In summary, in this assignment, I was able to fetch news data related to Bitcoin and Ethereum using the news apis. After fetching the data, I transformed the data into a panda dataframe by looping into the two news data.

I also used tokenizer tool to remove punctuation, stopword and lower case the entire articles. Then used counter, Ngrams and word cloud tools to basically count the words in each article and plot them. Also, with spacy, I was able to build entities name recognitions. And in the end I just listed all entities presented in the articles for both Bitcoin and Ethereum. 


### Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)





