# Amazon-reviews-sentimental-analysis

## Extracting information from Website:-  
Extracting information from Amazon using Beautiful soup. Information such as Review Title, Review Ratings, Review Content, Review Date are stored as list. Each of this information is stored as a feature to create a dataframe. 

## Text Cleaning:-  
Since we have got all text data in the form of a dataframe, now we will perform Text Cleaning on data such as  
- Tokenization — convert sentences to words   
- Removing unnecessary punctuation, tags   
- Lowering the text   
- Removing stop words — frequent words such as ”the”, ”is”, etc. that do not have specific semantic   
- Stemming — words are reduced to a root by removing inflection through dropping unnecessary characters,  usually a suffix.   
- Lemmatization — Another approach to remove inflection by determining the part of speech and utilizing  detailed database of the language.   
- Bag of Words   
- TF-IDF

## Sentiment Analysis:  
Since we have got all the cleaned data we will perform Sentiment Analysis using Sentiment Intensity Analyzer ,  with this we can extract pos, neg, neu, compound values. Now we can apply doc2vec and TFIDF Vectorizer and add  features such as numbr of words and number of characters. Once its done sort the top positive words and top  negative wordswith respect to pos and neg values. The top positive and negative words are displayed using wordcloud.
