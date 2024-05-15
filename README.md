# NLP-Based-Hybrid-Ensemble-for-Multilingual-Cyberbullying-Detection
This repository contains the implementation of a D-Ensemble model based on deep learning techniques to identify and remove cyberbullying comments, tested on English, Turkish, and Bengali datasets. The primary focus is on the Bengali dataset, but the D-Ensemble model's efficiency is also evaluated using Turkish and English languages.
NLP-Based Hybrid Ensemble for Multilingual Cyberbullying Detection
This repository contains the implementation of a D-Ensemble model based on deep learning techniques to identify and remove cyberbullying comments, tested on English, Turkish, and Bengali datasets. The primary focus is on the Bengali dataset, but the D-Ensemble model's efficiency is also evaluated using Turkish and English languages.

# Overview: 
This study developed a D-Ensemble model based on deep learning models as well as tested it with English and Turkish datasets to identify the bully comments in cyberspace so that they can removed and the rate of cyberbullying decreased. A Kaggle dataset with 44001 Bangla comments was used in the study for training, testing, and validation of the D-Ensemble model. This study primarily focused on the Bengali dataset but evaluated D-ensemble’s eﬃciency using Turkish and English languages. In this study, we used pre-processing methods including data cleaning, stop words removal, and tokenization. pre-trained BERT tokenization waas used for tokenizing texts and Explainable AI (Lime) to understand the procedure of the model. Single models’ results were compared with the D-Ensemble model where the D-Ensemble shows a higher eﬃciency in cyberbullying detection, it can be implemented to reduce cyberbullying problems in multiple languages. Bidirectional GRU (Bi-GRU), Bidirectional LSTM (Bi-LSTM), and Convolutional Neural Networks (CNN) were used as base models in this study, and the random forest was used as meta classiﬁers which showed 98.79% accuracy with 99.17 Precision and 98.98 F1-score for Bengali dataset.

# Datasets:
Kaggle dataset with 44,001 Bangla comments
English and Turkish datasets for additional evaluation
# Preprocessing:
Data cleaning
Stop words removal
Tokenization using pre-trained BERT
# Explainable AI:
LIME (Local Interpretable Model-agnostic Explanations) to understand the model's procedure
Models:

# Base Models: Bidirectional GRU (Bi-GRU), Bidirectional LSTM (Bi-LSTM), Convolutional Neural Networks (CNN)
# Meta Classifier: Random Forest
# Performance:
Accuracy: 98.79%
Precision: 99.17%
F1-score: 98.98% (for Bengali dataset)
# Keywords
D-Ensemble, Deep neural networks, Explainable AI (XAI), Cyberbullying, Ensemble Learning, Natural Language Processing, Black-box
# Highlights
The D-Ensemble model demonstrates higher efficiency in detecting cyberbullying compared to single models.
The approach is versatile and can be implemented for multilingual datasets to effectively reduce cyberbullying across different languages.





