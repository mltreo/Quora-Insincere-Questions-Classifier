# Quora-Insincere-Questions-Classifier
The code in this repo is all you need to make a first submission to the Quora-Insincere-Questions-Classification Kaggle Competition. 

   1. First nobebook (toxic content detector) uses the the FastAi library and is based on the approach of training a language model using pre-trained embeddings (WikiText 103.1) and then training a language classifier on top of it to predict the labels (targets). The fast.ai MOOC will be publicly available in Jan 2019
   
  2. Second notebook uses the Pytorch framework and trains a classifer using the average of several pre-trained embeddings (Glove, GoogleNews-vectors-negative300, paragram_300_sl999, wiki-news-300d-1M) and various architectures
