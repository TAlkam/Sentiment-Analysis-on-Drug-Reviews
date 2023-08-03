# Sentiment-Analysis-on-Drug-Reviews

This project is an exploration of sentiment analysis techniques applied to drug reviews. We use a dataset of drug reviews along with associated ratings, and our task is to build a model that can accurately predict the sentiment of a review.

## Dataset

The dataset used in this project is a set of drug reviews sourced from the UCI Machine Learning Repository. It consists of multiple fields, but we primarily make use of the review text and ratings. The ratings are used as a proxy for sentiment (positive, neutral, negative).

## Analysis Steps

1. **Data Preprocessing:** The raw review texts are cleaned and preprocessed for analysis. This involves removing special characters, converting to lower case, tokenization, and stemming/lemmatization.

2. **Exploratory Data Analysis (EDA):** We conduct an EDA to understand the distribution of sentiments, the most frequent words, and other characteristics of the dataset. We use word clouds, bar charts, and other visualization techniques for this analysis.

3. **Feature Extraction:** We convert the cleaned review texts into numerical features that can be used for training machine learning models. We use techniques like Bag-of-Words (BoW) and TF-IDF for this step.

4. **Model Training and Evaluation:** We train multiple machine learning models on the extracted features and evaluate their performance. The models used include Naive Bayes, Support Vector Machines (SVM), and Long Short-Term Memory (LSTM) networks. The evaluation metrics used are accuracy, precision, recall, and F1-score.

## Results

The performance of the trained models is summarized in the following table:

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Naive Bayes | 0.66 | 0.89 | 0.09 | 0.16 |
| Support Vector Machines | 0.70 | 0.74 | 0.90 | 0.81 |
| Long Short-Term Memory (LSTM) | 0.6467 | 0.42 | 0.65 | 0.51 |

## Contributing

If you're interested in contributing to this project, feel free to fork the repository and submit a pull request. We're always open to suggestions and improvements!
