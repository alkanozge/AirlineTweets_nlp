# Airport Tweet Analyzer

A simple web application that performs **sentiment analysis** and **topic-based clustering** on tweets related to airports and airlines.
Dataset: https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment


### 1. **Sentiment Analysis**
- Built with a trained **deep learning model** (`.h5` file from Keras).
- Classifies each tweet into one of three sentiments with confidence scores.

### 2. **Tweet Clustering**
- Based on **KMeans** clustering using **KeyBERT** embeddings.
- Clusters tweets by topic, and assigns cluster names based on top keywords.



