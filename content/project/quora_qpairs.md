+++
title = "Detection of Quora Question duplicates"
date = 2017-11-12

 summary = "Machine Learning Project to identify question pairs that have the same intent?"

 # tags = ["machine-learning", "natural-language-processing", "deep-learning"]

# Links (optional).
url_pdf = "https://www.slideshare.net/JayavardhanReddyPedd/duplicatequoraquestiondetection"
url_code = "https://github.com/jayavardhanr/Quora-Question-Answering-Pairs-Project"
url_dataset = "https://www.kaggle.com/c/quora-question-pairs"
url_project = "https://github.com/jayavardhanr/Quora-Question-Answering-Pairs-Project"
url_slides = "https://www.slideshare.net/JayavardhanReddyPedd/duplicatequoraquestiondetection"

 url_custom = []

# Does the content use math formatting?
 math = true

# Does the content use source code highlighting?
 highlight = true

+++

Finding an answer to any question is becoming easier by the day but finding the “best” answer is getting increasingly difficult. Our project focuses on identifying questions with similar intent in question answering sites, specifically, the site Quora. 

Given a dataset consisting of question pairs, we try to classify the given pairs as duplicate or not duplicate. 

Identifying duplicate questions is not an easy task since questions that have no words in common could still have the same intent and questions with almost the same words might have different intent. We tried to tackle this problem through elegant feature engineering using one-hot features, questions length information, Word Embedding both Glove as well as Word2Vec embeddings. We implemented both simpler Machine Learning models like Random Forest, SVM, Logistic regression and also complex Neural Network models like CNN, LSTM, Bidirectional LSTM Networks using the Siamese architecture. The performance of models has been compared and a detailed analysis was performed about the different features and parameter tuning for the different models implemented.

