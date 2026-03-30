📰 Multiclass News Classification using Machine Learning
📌 Project Overview

This project focuses on building a Multiclass News Classifier using Machine Learning and Natural Language Processing (NLP) techniques. The system automatically categorizes news articles into four categories:

🌍 World
🏏 Sports
💼 Business
🔬 Sci/Tech

The goal is to efficiently organize large volumes of news data without manual intervention.

🎯 Objectives
Automate classification of news articles into multiple categories
Apply NLP techniques for text processing
Compare machine learning models for best performance
Provide real-time prediction through a simple interface
📂 Dataset
Dataset Used: AG News Dataset
Contains 120,000+ news articles
Each record includes:
Title
Description
Category Label
⚙️ Tech Stack
Python 🐍
Pandas & NumPy
Scikit-learn
Matplotlib & Seaborn
Google Colab
🔄 Project Workflow
1. Data Preprocessing
Renamed columns
Merged title + description into a single text column
Converted labels to meaningful categories
2. Feature Extraction
Used TF-IDF Vectorization
Converted text into numerical form for model training
3. Model Training

Two models were implemented:

Multinomial Naive Bayes
Logistic Regression
4. Model Evaluation
Accuracy Score
Classification Report (Precision, Recall, F1-score)
Confusion Matrix

📊 As shown in the confusion matrix, the model performs well across all categories with minimal misclassification.

📈 Results
Naive Bayes Accuracy: ~89%
Logistic Regression Accuracy: ~90%
Balanced performance across all categories

✔ Final Model Selected: Multinomial Naive Bayes (based on speed & efficiency)

💻 Features
Real-time news classification
Interactive prediction interface using widgets
Efficient handling of large text data
