Documents-Search-Engine
=======================

Documents-Search-Engine is an Information Retrieval System that use Term frecuency-inverse Document Frecuency and cosine similarity to retreive the most relevants documents given a query

#### Usage
Run `python search.py` for the test

Run your own query `python search.py "my own query"`

##### Term frecuency-inverse Document Frecuency

TF-IDF is a numerical statistics which reflects how important a word is to a document. The tf-idf value increases proportionally to the number of times a word appears in the document, but is offset by the frequency of the word in the corpus, which helps to control for the fact that some words are generally more common than others.

[Wiki](http://en.wikipedia.org/wiki/Tf-idf)

##### Cosine Similarity

Cosine similarity is a measure of similarity between two vectors and in information retrieval gives a useful measure of how similar two documents are likely to be in terms of their subject matter.

[Wiki](http://en.wikipedia.org/wiki/Cosine_similarity)


##### Porter Stemmer

The code provide a set of documents (60 stories written by Haggard Rider) and a file with query solutions for the tests
The PorterStemmer algorithm create a stemmed copy of each document if it doesn't exist
