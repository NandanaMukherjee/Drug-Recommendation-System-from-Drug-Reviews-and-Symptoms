# Drug-Recommendation-System-from-Drug-Reviews-and-Symptoms
This project aims to predict disease names and recommend the top 3 drugs for a specific condition based on user-provided drug reviews and symptoms. It uses Natural Language Processing (NLP) techniques to process the textual data and employs machine learning algorithms for prediction.

Methodology:
Data Preprocessing: The dataset of drug reviews and symptoms is processed using techniques like tokenization, stopword removal, and lemmatization.
TF-IDF: The Term Frequency-Inverse Document Frequency (TF-IDF) vectorizer is used to convert text data into numerical representations for machine learning.
Algorithms:
Naive Bayes: The Naive Bayes classifier is used to classify disease names based on the processed reviews and symptoms.
Passive-Aggressive Classifier: This algorithm is applied to refine the predictions and improve the accuracy of disease identification.
Technologies Used:
Python: The core programming language for data manipulation, NLP, and model building.
Scikit-learn: Used for implementing machine learning models (Naive Bayes and Passive-Aggressive Classifier).
NLTK: For natural language processing tasks like tokenization, stopword removal, and text preprocessing.
Pandas & NumPy: For handling and processing the dataset.
