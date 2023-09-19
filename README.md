# IMDB-Movie-Review-Sentiment-Analysis

This repository contains a project focused on sentiment analysis of IMDB movie reviews. The dataset used for this project consists of 25,000 movie reviews, making it a substantial dataset for binary sentiment classification. The goal of the project is to predict whether a review is positive or negative.

## Task

The primary task of this project is to predict the sentiment (positive or negative) of IMDB movie reviews using classification techniques. The implementation steps include:

### Data Preprocessing
- Remove punctuation from text data.
- Perform tokenization.
- Remove stopwords.
- Perform lemmatization or stemming.

### TF-IDF Vectorization
- Convert preprocessed text data into TF-IDF vectors for modeling.

### Model Selection
- Explore parameter settings using GridSearchCV on Random Forest and Gradient Boosting Classifier.
- Use XGBoost instead of Gradient Boosting if GridSearchCV is taking too long.
- Select the best-performing model based on evaluation metrics.

### Final Model Evaluation
- Evaluate the best model using the chosen parameter settings.
- Report evaluation metrics for model performance.
