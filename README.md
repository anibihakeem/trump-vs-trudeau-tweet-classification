# trump-vs-trudeau-tweet-classification
A machine learning classifier that knows whether President Trump or Prime Minister Trudeau is tweeting

## Overview
This project aims to classify tweets by their authors using machine learning. Specifically, it uses a text classification approach to distinguish between tweets written by Donald Trump and Justin Trudeau.

## Description
The notebook consists of various sections including data loading, preprocessing, model training, and testing. Key steps in the process are:

- Data Loading: Tweets from Donald Trump and Justin Trudeau are loaded into the environment.<br>
- Data Preprocessing: The tweets are cleaned and prepared for modeling. This involves removing special characters, tokenizing the text, and converting it into a suitable format for the machine learning model.<br>
- Feature Extraction: Term Frequency-Inverse Document Frequency (TF-IDF) vectorization is used to transform the text data into a format that can be used for machine learning modeling.<br>
- Model Training: A Support Vector Machine (SVM) model is trained on the processed tweet data.<br>
- Model Testing: The model is tested with sample tweets to predict the author accurately.<br>

## Results
The model successfully classifies tweets between the two authors. Sample predictions made by the model are as follows:

For a tweet labeled as Trump's, the model prediction is Donald J. Trump.
For a tweet labeled as Trudeau's, the model prediction is Justin Trudeau.
