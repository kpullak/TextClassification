# Project Details:

Titled - Comparative Analysis of different deep neural network architectures: CNN, RNN and HAN (This is work done for the Capstone Project for graduate level course - CS 591 Algorithms for Data Guided Business Intelligence).

In this capstone project, performed a comparative analysis of different deep neural network architectures: CNN, RNN and HAN (Convolutional, Recurrent, Hierarchical Attention Network models) for Text Classification using GloVe Embeddings on IMDB movie review dataset from Kaggle.

# Author: Krishnachaitanya Pullakandam

# Dataset:
	Kaggle IMDB Sentiment Reviews (Link: http://www.cs.cornell.edu/people/pabo/movie-review-data/)


# Libraries/Dependencies:
        1) pickle
        2) pandas
	2) numpy
	3) keras.models, keras.layers, keras.utils, keras.preprocessing
	4) collections framework
	5) BeautifulSoup
	6) sklearn
	7) Glove Data (glove.6B.100d.txt)
	8) Kaggle Dataset (labeledTrainData.tsv)


# Instructions to Run:

	python cnn.py
	python rnn.py
	python han.py
	

# Observations:
Achieved the following accuracies using each of the models: 

1. CNN(85\%) 
2. RNN(81\%) and 
3. HAN(92\%) 


# References:

	1) https://www.nltk.org/api/nltk.tokenize.html
	2) https://keras.io/layers/writing-your-own-keras-layers/
	3) https://machinelearningmastery.com/develop-word-embedding-model-predicting-movie-review-sentiment/
	4) https://github.com/FlorisHoogenboom/keras-han-for-docla
	5) https://richliao.github.io/supervised/classification/2016/12/26/textclassifier-HATN/
	6) https://medium.com/jatana/report-on-text-classification-using-cnn-rnn-han-f0e887214d5f
	7) https://nlp.stanford.edu/projects/glove/
	8) https://www.kaggle.com/c/word2vec-nlp-tutorial/data
