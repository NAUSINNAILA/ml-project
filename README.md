# ml-project
In this project will implement topic modeling using LDA on the Trip Advisor Hotel Reviews
dataset which is available on kaggle [1]. We will focus on the text reviews. Each review can be
considered as one document. Before application of LDA for topic modeling, some
text-preprocessing is required.
Do the following:
1) Remove the stopwords
2) Apply tokenization, lemmatization and stemming to the text data.
Read about the above procedures. These are standard text preprocessing techniques for many
NLP tasks. You can use the python nltk toolkit to perform the above tasks. You can also display
a word cloud just to gain an idea of word distribution in your corpus.
Next create your dictionary and also convert the documents to the bag of words model. You can
use the gensim module for the tasks. You can also use
sklearn.feature_extraction.text
count vectorizer to create document term matrix. Apply LDA on the data using either
gensim model or sklearn.decomposition LatentDirichletAllocation module.
Check the results for different values of K i.e. no. of topics that you assume. Looking at the high
probability words in the obtained topics try to analyze the different reviews and explain your
analysis and observations. You can use various plots or some print statements to support your
conclusions.
