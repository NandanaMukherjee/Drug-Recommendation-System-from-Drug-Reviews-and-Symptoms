# Drug-Recommendation-System-from-Drug-Reviews-and-Symptoms

## Overview:
This project aims to predict disease names and recommend the top 3 drugs for a specific condition based on user-provided drug reviews and symptoms. It uses Natural Language Processing (NLP) techniques to process the textual data and employs machine learning algorithms for prediction.

## Contents:

* [Methodology](#Methodology)
* [Work Flow Diagram](#WorkFlowDiagram)
* [Key Code Sections and Functions](#KeyCodeSectionsandFunctions)
* [Conclusion](#Conclusion)


## Dataset Drive Link:
https://docs.google.com/spreadsheets/d/1zJZvBAPsv-BWvNjKc0HUmcQrrNRBr7zLkbuqhyHcdDU/edit?usp=sharing

## Methodology:

###   1. Data Loading and Exploration:
       The dataset is loaded, and rows are filtered based on certain conditions (e.g., "Birth Control", "Depression", etc.).
      Exploratory Data Analysis (EDA) includes word clouds for visualizing the most frequent words in reviews for different conditions.
      Text Preprocessing:

 ### 2. Text Processing :
      Stop-words (commonly used words like "the", "a", "is", etc.) are removed, and lemmatization is done to reduce words to their base form.
      
###  3. Text Vectorization:
     Various techniques are used for transforming text into numerical features:
     Count Vectorizer (Bag of Words): Counts the frequency of each word in the text.
     TF-IDF (Term Frequency-Inverse Document Frequency): Weighs words based on their importance in a document and across all documents.
     
###  4. Modeling:
       Naive Bayes and Passive-Aggressive Classifiers are trained using the features obtained from the TF-IDF vectorizer.
       The models are evaluated using accuracy and confusion matrices to check for performance.
       
### 5. Feature Importance:
        For the Passive-Aggressive Classifier, the top positive and negative features are extracted, which indicates which words most strongly influence the classification decision.

###  6. Sample Prediction:
        The model is used to predict the condition of a new review, with an example review about Tekturna being classified.
        Cosine Similarity for Recommendation:
        A similarity-based drug recommendation approach is added, where new reviews are compared with existing reviews in the dataset based on cosine similarity.

## Work Flow Diagram : 

![WhatsApp Image 2024-11-14 at 9 12 06 PM](https://github.com/user-attachments/assets/4510f09f-8b50-491c-892c-f94bc11211fe)


## Key Code Sections and Functions:
   ### 1.Data Cleaning and Preprocessing
   ### 2.Vectorization
   ### 3.Model Training
   ### 4.Confusion Matrix Plot
   ### 5.Feature Importance Extraction
   ### 6.Cosine Similarity for Drug Recommendation

## Conclusion:
The drug recommendation system built using machine learning techniques aims to predict and classify conditions like "Birth Control," "Depression," "High Blood Pressure," and "Pain" based on user reviews and feedback. The system leverages text preprocessing techniques such as stopword removal, lemmatization, and feature extraction through methods like TF-IDF (Term Frequency-Inverse Document Frequency) to transform the textual data into numerical features.
Practical Applications: The drug recommendation model can be extended to suggest appropriate medications based on user reviews or conditions, making it a valuable tool in the healthcare domain. It could assist healthcare providers in understanding patient preferences or recommending suitable treatments.
