# fintech-nlp-homework

This repository contains the Jupyter notebook, accompanied with the natural learning processing tools and libraries as part of the Fintech homework assignment Unit 12—Tales from the Crypto.

In this homework, we have performed sentiment analysis on the latest news articles featuring Bitcoin and Ethereum. We have also used NLP techniques to understand the other factors involved with the coin prices such as common words, phrases, organizations and entities mentioned in the articles.


## Files

### [Crypto Sentiment](crypto_sentiment.ipynb)

For this section, these are the following tasks:

#### 1 - Sentiment Analysis

- Use the newsapi to pull the latest news articles for Bitcoin and Ethereum 

- Read the api key environment variable

- Create a newsapi client

- Fetch the Bitcoin and Ethereum news articles from newsapi.org by using get_everything function

- Create a DataFrame of sentiment scores for each coin.

- Create summary statistic tables of each dataframes.

#### 2 - Natural Language Processing

In this section, we will use NLTK and Python to perform the following tasks for the given coins:

* Tokenize
  
For this section, We will perform the following tasks to preprocess the text:
       
    - Tokenization: Tokenization is a process of creating tokens by splitting the larger text into 
    smaller sentences, words or phrases.
    
    - Lemmatization: Lemmatization is the process of converting a word to its base form. 
    
    - Lowercase each word.
    
    - Remove Punctuation.
    
    - Remove Stopwords: Stopwords are the words which does not add much meaning to the sentence, 
    if we remove the stopwords the meaning of the sentence does not change. 
    
    - Create a new tokens column for Bitcoin and Ethereum dataframe

* NGrams and Frequency Analysis
   
In this section, we will look at the ngrams and word frequency for each coin:

    - Use NLTK to produce the n-grams for N = 2.
     
    - List the top 10 words for each coin.
    
* Word Clouds

In this section, we will generate word clouds for each coin to summarize the news for each coin:
   
      - Create a wordcloud function to generate the word clouds for the Bitcoin nd Ethereum. 
      
* Named Entity Recognition

[NER](https://en.wikipedia.org/wiki/Named-entity_recognition) helps us to identify the key elements in a text, like names of people, places, brands, organization etc. It also known as entity identification, entity chunking, and entity extraction.

In this section, we will build a named entity recognition model for both Bitcoin and Ethereum, then visualize the tags using SpaCy.

Tags is a part-of-speech tag which signifies whether the word is a noun, adjective, verb and so on.

    - Download the language model for SpaCy
    
    - Load the spaCy model
    
    - Concatenate all of the Bitcoin and Ethereum text together
    
    - Render the visualization

 
## Resources: 
  
 * [NER](https://en.wikipedia.org/wiki/Named-entity_recognition)
 
 * [POS Tagging](https://www.geeksforgeeks.org/nlp-part-of-speech-default-tagging/#:~:text=It%20is%20a%20process%20of,part%2Dof%2Dspeech%20tagging)
 

