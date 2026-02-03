- In NLP we first tokenize the paragraph(corpus) 
  -   using tokenize library
- then we apply stemming to get root of the word( eaten->eat)
  - to do so that we use stemming or lemmatization 
    -  libraries( PorterStemmer,RegexpStemmer,snowballsstemmer ,WordNetLemmatizer) 
        - before Lemmatize we need to remove the stop word(he,could,we)
        - in Lemmatizatio we need to tag words as noun,pronoun or part of speech to work properly.
            - for part of speech tagging we use nltk.post_tag method



stemming