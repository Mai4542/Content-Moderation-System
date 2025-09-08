Content Moderation System
🔎 Short Overview

A machine learning-based system for automatic content moderation, detecting toxic, spam, and safe content.
The system combines rule-based filters with ML classifiers to simulate real-world moderation tools used by platforms like Facebook, Twitter, YouTube, and OpenAI.

👉 Open Colab Notebook

📌 Project Overview

This project implements a Content Moderation System that automatically classifies and filters user-generated content using machine learning techniques.

🏗️ System Architecture
🔹 Text Preprocessing Module

Text normalization and cleaning

Feature extraction (length, word count, capitalization ratio, etc.)

URL, mention, and hashtag detection

🔹 Rule-Based Filter

Offensive keyword blacklist

Pattern matching for spam/promotional content

Excessive capitalization and character repetition detection

🔹 Machine Learning Classifier

Algorithms: Naive Bayes, Logistic Regression, SVM, Random Forest

TF-IDF vectorization

Multi-class classification: toxic, spam, safe

🔹 Risk Assessment Engine

Weighted scoring combining rule-based + ML predictions

Configurable confidence thresholds

Dynamic decision making based on risk scores

📊 Dataset

The dataset used in this project is available here:
Google Drive Dataset

🚀 Google Colab Notebook

You can run and explore the project notebook here:
👉 Open Colab Notebook

👩‍💻 Team Members

Mai Mohamed

Farida Montasser

Hanen Mohamed
