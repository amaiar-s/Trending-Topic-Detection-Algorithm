# Trending-Topic-Detection-Algorithm
This project implements a trending topic detection system using the BNgram algorithm, inspired by the paper "Sensing Trending Topics in Twitter" by L. M. Aiello et al. The goal is to identify emerging trends in social media by analyzing temporal patterns in n-grams extracted from tweets.

## The pipeline includes:
- Data Collection: Fetching tweets within a specified time range.
- Preprocessing: Cleaning text, filtering English tweets, and tokenizing words.
- N-Gram Generation: Extracting sequences of words (e.g., trigrams) for analysis.
- Relevance Scoring: Evaluating n-grams based on their occurrence over time.
- NER Boosting & Clustering: Enhancing named entities and grouping similar topics.
- Ranking: Identifying the most relevant trending topics.

The algorithm allows customization of parameters like n-gram size, clustering, and NER application. Despite computational challenges and the lack of a ground truth dataset, this project demonstrates a scalable approach to detecting trends in real-time social media data.
