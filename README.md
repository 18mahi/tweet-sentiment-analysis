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
