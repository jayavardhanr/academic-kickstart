+++
title = "Detection of Quora Question duplicates"
date = 2017-11-12

summary = "Machine Learning Project to identify question pairs that have the same intent?"

+++

Finding an answer to any question is becoming easier by the day but finding the “best” answer is getting increasingly difficult. Our project focuses on identifying questions with similar intent in question answering sites, specifically, the site Quora. Given a dataset consisting of question pairs, we try to classify the given pairs as duplicate or not duplicate. 

Identifying duplicate questions is not an easy task since questions that have no words in common could still have the same intent and questions with almost the same words might have different intent. 

  * I tried to tackle this problem through elegant feature engineering using one-hot features, questions length information, Word Embedding both Glove as well as Word2Vec embeddings. 
  * I implemented both traditional machine learning models like Random Forest, SVM, Logistic regression and also complex Neural Network models like CNN, LSTM, Bidirectional LSTM Networks using the Siamese architecture. 
  * The performance of different models was compared and a ablation study was performed for the different features and parameter used for the different models implemented.
  * 2-layer Bidirectional LSTM model with dropout produced the best Log-loss of 0.25 on public test-seton Kaggle.
  
 **[Github Repo](https://github.com/jayavardhanr/Quora-Question-Answering-Pairs-Project)**
 
 **[Slides](https://www.slideshare.net/JayavardhanReddyPedd/duplicatequoraquestiondetection)**
 




