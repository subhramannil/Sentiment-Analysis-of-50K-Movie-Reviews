# Sentiment-Analysis-of-50K-Movie-Reviews

## Overview

This project, developed for the Fellowship.AI application by Subhranil Das, a 4th-year Computer Science student at the Institute of Engineering & Management (IEM), Kolkata, performs sentiment analysis on the IMDB Dataset of 50K Movie Reviews. Using a bidirectional LSTM neural network, the model classifies reviews as positive or negative, achieving a test accuracy of [insert test_acc, e.g., 0.87]. Key features include text preprocessing with WordNetLemmatizer, word cloud visualizations, and an interactive tool for user-input predictions.

Demo Video: [Insert your YouTube/Google Drive link here, e.g., https://youtube.com/watch?v=XXXX or https://drive.google.com/file/d/XXXX/view]

## Features

Dataset: 50,000 IMDB movie reviews (25,000 positive, 25,000 negative).


Preprocessing: Cleans text by removing HTML tags, URLs, and stopwords, and applies WordNetLemmatizer (e.g., "I loved the movies" → "love movie").


Model: Bidirectional LSTM with embedding layer, trained on 40,000 reviews, tested on 10,000.

Visualizations: Sentiment distribution plot, word clouds for positive/negative reviews, training history plot.


Interactive Tool: Predicts sentiment for user-input reviews with confidence scores.

Requirements

To run this project, install the following Python libraries:

pip install pandas numpy tensorflow nltk matplotlib seaborn wordcloud

Additionally, download NLTK resources:

import nltk
nltk.download('stopwords')
nltk.download('wordnet')
