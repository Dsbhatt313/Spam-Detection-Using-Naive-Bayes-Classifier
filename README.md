# Spam Detection in YouTube Comments Using Naive Bayes

Project Overview

This project implements a Naive Bayes classifier to detect spam comments in YouTube data with high accuracy (96%). The model uses text data preprocessing and feature extraction techniques to classify comments as spam or non-spam, making it a useful tool for automated moderation.

Project Structure

Data Collection: Merged multiple CSV files containing YouTube comments, cleaned the dataset, and removed irrelevant columns.

Feature Engineering: Employed CountVectorizer to convert text comments into numerical features by tokenizing and counting word frequencies.

Model Development: Built a Naive Bayes classifier (MultinomialNB) and trained it on labeled comment data.

Evaluation: Achieved 96% accuracy, evaluated model performance using confusion matrices and classification reports.

Key Files

data/: Contains the dataset (YouTube comment CSV files).

notebook.ipynb: Jupyter notebook with data processing, model training, and evaluation steps.

Results

The model performs well, accurately distinguishing spam from non-spam comments with minimal false positives, achieving a balanced classification suitable for practical applications in content moderation.

