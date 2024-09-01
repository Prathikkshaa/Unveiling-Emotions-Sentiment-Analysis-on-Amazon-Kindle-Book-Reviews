# Sentiment Analysis on Amazon Kindle Book Reviews

## Overview
This project involves performing sentiment analysis on Amazon Kindle book reviews using a dataset from Kaggle. The dataset includes various features such as product IDs, helpfulness ratings, review text, and overall product ratings. The primary focus of this analysis is on two key columns: `reviewText` (independent variable) and `rating` (dependent variable). The dataset comprises 12,000 reviews, with ratings above 3 classified as positive (0) and ratings below 3 as negative (1).

## Features
- **Dataset**: Amazon Kindle book reviews dataset from Kaggle.
- **Data Columns**: `reviewText`, `rating`, and other features like product IDs and helpfulness ratings.
- **Preprocessing**: Includes text normalization, punctuation removal, stopwords removal, URL removal, HTML tag removal, email removal, and lemmatization.
- **Text Representation**: Bag of Words (BOW) and Term Frequency-Inverse Document Frequency (TF-IDF) methods.
- **Model**: Gaussian Naive Bayes classifier.
- **Performance Metrics**: Confusion matrix, accuracy, precision, recall, and F1-score.

## Data Preprocessing
1. **Text Normalization**: Converted all text to lowercase.
2. **Cleaning**: Removed punctuation, stopwords, URLs, HTML tags, and emails.
3. **Lemmatization**: Reduced words to their base forms for uniformity.

## Text Representation
1. **Bag of Words (BOW)**: Transformed text into a matrix of token counts.
2. **Term Frequency-Inverse Document Frequency (TF-IDF)**: Converted text into a matrix of TF-IDF features.

## Model Building
- **Classifier**: Gaussian Naive Bayes.
- **Training & Testing**: Trained and tested the model using both BOW and TF-IDF features.
- **Evaluation**: Assessed model performance using accuracy, precision, recall, F1-score, and confusion matrix.

## Results
The sentiment analysis model achieved approximately 59% accuracy in both BOW and TF-IDF approaches. The model demonstrated a reasonable ability to classify sentiments, particularly in distinguishing between positive and negative reviews. This project illustrates the effectiveness of natural language processing (NLP) techniques and machine learning in extracting insights from customer feedback on Amazon Kindle books.

## Installation
To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-kindle-reviews.git
   cd sentiment-analysis-kindle-reviews
