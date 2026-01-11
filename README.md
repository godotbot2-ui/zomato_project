🍽️ Zomato Restaurant Analytics & Review Intelligence

A comprehensive machine learning and NLP-based data analytics project that explores restaurant performance, customer sentiment, and review-driven insights using real-world Zomato restaurant and review data.

This project combines exploratory data analysis, hypothesis testing, natural language processing, feature engineering, and predictive modeling to extract actionable insights from structured and unstructured data.

📌 Project Overview

Online food platforms generate massive amounts of textual and numerical data, yet much of it remains underutilized.
This project aims to bridge that gap by analyzing:

How cost, cuisine, and review engagement affect restaurant ratings

Patterns hidden inside customer reviews using NLP

Whether text-derived features improve predictive performance

Statistical relationships validated through hypothesis testing

The project is designed and documented as if presented in a technical interview.

🎯 Objectives

Perform end-to-end data analysis on restaurant metadata and reviews

Apply Natural Language Processing (NLP) on customer reviews

Validate assumptions using statistical hypothesis testing

Engineer meaningful features from text and metadata

Build and evaluate machine learning models for rating prediction

Present insights in a clear, explainable, and business-relevant manner

📂 Dataset Description
1. Restaurant Metadata

Includes:

Restaurant name

Cost for two

Cuisines

Location & collections

Timings

2. Customer Reviews

Includes:

Reviewer name

Review text

Rating

Timestamp

Review length

Engagement indicators

The two datasets are merged and cleaned to form a unified analytical dataset.

🔍 Exploratory Data Analysis (EDA)

Key analyses performed:

Rating distribution analysis

Cost vs rating relationships

Cuisine-wise performance comparison

Review length vs engagement

Outlier detection and normalization

Visualizations include:

Histograms

Box plots

Scatter plots

Pair plots

Correlation heatmaps

🧠 Textual Data Processing (NLP Pipeline)

The NLP pipeline follows industry best practices:

Expand contractions

Convert text to lowercase

Remove punctuation, URLs, digits, and noise

Remove stopwords and extra whitespaces

Tokenization

Text normalization (lemmatization)

Part-of-Speech (POS) tagging

Text vectorization using TF-IDF

🔎 TF-IDF Technique Used

Word-level TF-IDF

Unigrams & bigrams

Stopword filtering

Justification: balances interpretability and performance for medium-sized datasets

🧪 Hypothesis Testing

Statistical tests were conducted to validate assumptions such as:

Do higher-cost restaurants receive significantly different ratings?

Does review engagement correlate with ratings?

Do cuisine categories differ significantly in customer perception?

Tests used:

Welch’s Independent Samples t-test

Correlation analysis

Distribution comparison

Each hypothesis is clearly stated, tested, and interpreted.

🏗️ Feature Engineering

Key engineered features:

Review length

Log-transformed cost

Scaled numerical features

Cuisine one-hot encodings

Encoded categorical variables

Engagement metrics

TF-IDF vectors

Missing values handled using:

Mean imputation (numerical)

Mode imputation (categorical)

🤖 Machine Learning Models

Models explored include:

Linear Regression

Regularized models

Tree-based approaches (where applicable)

Training pipeline:

Train-test split (80/20)

Feature scaling

Class imbalance handling

Model evaluation using:

RMSE

MAE

R² Score

📊 Results & Insights

Key findings:

Cost alone does not guarantee higher ratings

Certain cuisines consistently outperform others

Review length and engagement are strong indicators of sentiment

Text-based features significantly enhance prediction quality

NLP-derived features improve explainability

🚀 Future Enhancements

Sentiment analysis using transformer-based models

Aspect-based sentiment extraction

Review summarization

Deep learning models (LSTM / BERT)

Time-series analysis on rating trends

Recommendation system integration

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

NLTK

Imbalanced-learn

Jupyter Notebook
