This project aims to classify Wikipedia articles into medical and non-medical categories using Natural Language Processing (NLP) techniques. The classification is performed based on the textual content of the articles.

Project Structure
Data Collection:

Wikipedia articles are collected using the Wikipedia API.
Two categories, medical and non-medical, are chosen to create a labeled dataset.
Text Preprocessing:

Text from Wikipedia articles is preprocessed using NLTK for tasks such as tokenization, stemming, and stop-word removal.
HTML tags and special characters are removed to clean the text.
Feature Extraction:

Bag of Words (BoW) representation is used to convert text data into numerical vectors.
CountVectorizer from scikit-learn is employed for feature extraction.
Model Training:

Multinomial Naive Bayes and Logistic Regression classifiers are trained on the labeled dataset.
Evaluation:

Model accuracy and classification reports are generated to evaluate the performance of the classifiers.
Dependencies
wikipedia
requests
nltk
beautifulsoup4
scikit-learn
