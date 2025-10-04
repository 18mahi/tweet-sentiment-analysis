# tweet-sentiment-analysis
This repository contains an intermediate-level tweet sentiment analysis model built using Python, Scikit-learn, TextBlob, and Plotly. The project demonstrates feature engineering, machine learning, and interactive visualization in a complete workflow, making it ideal for portfolios and learning purposes.

# Project Overview
The model classifies tweets into five sentiment categories: happy, angry, sad, excited, and neutral. It combines TF-IDF text features with intermediate-level engineered features, including:
Emoji sentiment scoring
Polarity & subjectivity (TextBlob)
Exclamation and question counts
Word count and average word length
Hashtags, mentions, and capital letter ratio
The project leverages a RandomForest classifier trained on a synthetic dataset, showcasing feature importance, prediction probabilities, and interactive visualizations for both evaluation and user inputs.

# Key Features
Text Preprocessing: Cleans tweets by removing URLs, mentions, hashtags, and punctuation.
Feature Engineering: Combines text-based TF-IDF vectors with numeric sentiment and structural features.
Model Evaluation: Includes accuracy metrics, classification report, and confusion matrix.

# Visualization:
Probability bar charts for individual predictions using Plotly.
Top feature importance visualized with Matplotlib.
Dynamic User Input: Users can type custom tweets and receive predicted sentiment and probability distribution interactively.

# Technologies & Libraries
-Python 3.x
-Pandas & Numpy
-Scikit-learn
-TextBlob
-Matplotlib & Seaborn
-Plotly

# How to Use
Run the notebook in Jupyter.
Explore the pre-generated test predictions and visualizations.
Use the dynamic input section to classify any custom tweet.
Observe probability bars and feature contributions for interpretability.

# Learning Outcomes
This project demonstrates practical NLP techniques, intermediate-level feature engineering, model evaluation, and interactive visualization, making it an excellent addition to a data science portfolio. It also provides a foundation to explore more advanced topics like bigram/trigram TF-IDF, deep learning, or sentiment analysis on larger datasets.

<img width="814" height="292" alt="image" src="https://github.com/user-attachments/assets/91ce01c0-e9dc-4bf0-8e0e-0aada90acb06" />

<img width="798" height="286" alt="image" src="https://github.com/user-attachments/assets/53f65548-5e8c-4b88-809f-13123ebaa7a4" />

<img width="804" height="289" alt="image" src="https://github.com/user-attachments/assets/bfb3ae38-17fc-47e7-a132-cd043513cf0e" />

<img width="809" height="285" alt="image" src="https://github.com/user-attachments/assets/ac55d7a2-08e8-434f-9486-c410de99bc88" />

<img width="814" height="295" alt="image" src="https://github.com/user-attachments/assets/a23385cf-cb9b-4d0b-857a-210fa7f0decb" />

<img width="812" height="283" alt="image" src="https://github.com/user-attachments/assets/bee285e2-387e-4662-acfa-994f8120cee8" />

<img width="771" height="268" alt="image" src="https://github.com/user-attachments/assets/02c6bc3b-cc80-4384-b284-b5618594b58b" />
