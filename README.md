# Predicting-Popularity-of-Online-news-articles

# Online News Popularity Prediction

This project leverages machine learning to predict the popularity of online news articles. By analyzing various content features, we aim to classify articles as "Popular" or "Unpopular" based on their share counts relative to the median.

## Abstract
In the hyper-competitive social media landscape, content creators face the challenge of not only reaching targeted audiences but also maximizing engagement. This project uses machine learning to predict the popularity of online content, framing the task as a binary classification. By analyzing features such as word statistics, category, sentiment, and keywords, our model achieved an accuracy of 66%.

## Introduction
Predicting the popularity of online news articles is crucial for content creators, news organizations, and marketers. Understanding which articles are likely to resonate with audiences and generate high engagement allows for informed decision-making, leading to increased reach and success. This project uses the UCI Online News Popularity Dataset to develop a model capable of classifying articles as "Popular" or "Unpopular."

## Data Description
The dataset used in this project is from the UCI Machine Learning Repository and contains 39,644 records with 60 features each. These features are categorized into content, links, digital media, keywords, article category, publication day, and natural language processing (NLP) features.

- **Source:** UCI Machine Learning Repository - [Online News Popularity Dataset](https://archive.ics.uci.edu/dataset/332/online+news+popularity)
- **Website:** Mashable
- **Number of Records:** 39,644
- **Number of Features:** 60 features + 1 target

## Exploratory Data Analysis
Our EDA involved separating columns into distinct categories, data cleaning, and visualizing distributions and correlations. Key steps included:
- Handling outliers with KNN Imputer
- Using Pearson's Correlation for continuous variables
- Applying Chi-squared tests for categorical variables

## Model Selection and Evaluation
We experimented with several machine learning models, including:
1. Logistic Regression (Baseline, with Regularization, with PCA)
2. Naïve Bayes
3. Neural Network

Each model was evaluated based on its accuracy in classifying articles as popular or unpopular.

## Results
Our best model achieved an accuracy of 66%. This predictive model provides valuable insights for content creators, helping them make informed decisions about resource allocation and content creation strategies.

## Conclusion
This project demonstrates the potential of machine learning in predicting the popularity of online news articles. By leveraging various content features, we can provide actionable insights that help content creators thrive in the digital age.

