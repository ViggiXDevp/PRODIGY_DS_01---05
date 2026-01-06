# Twitter Sentiment Analysis – Task 4 📱💭

## Overview 🎯
Analyzed and visualized **sentiment patterns in social media data** to understand public opinion toward specific topics/brands using **Naive Bayes classifier** on Twitter Entity Sentiment Analysis dataset from Kaggle.  
Focused on sentiment distribution across entities and creating business-ready visualizations. 📊

## Dataset 📋
- **Name:** Twitter Entity Sentiment Analysis 
- **Source:** [Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis) 
- **Columns:** `tweet_id`, `text`, `entity`, `sentiment` (positive/negative/neutral/irrelevant) 

## What I Implemented ✅
- Loaded dataset using `pandas` and inspected structure (rows, columns, sentiment counts) 🔍
- **Text preprocessing:** Removed URLs, mentions, hashtags, stopwords; lowercase conversion ✂️
- **Feature extraction:** TF-IDF vectorization (max_features=5000) ⚙️
- **Modeling:** Trained **Naive Bayes (MultinomialNB)** with 80/20 train-test split 🎯
- **Evaluation:** Accuracy, F1-score, confusion matrix 📈
- **Visualizations created:**
  - Sentiment distribution **pie chart** 🥧
  - Entity-wise sentiment **bar plots** 📊
  - Positive vs negative **word clouds** ☁️
  - **Confusion matrix heatmap** 🔥

## Tech Stack 🛠️
- **Language:** Python 🐍
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `wordcloud`
- **Environment:** Jupyter Notebook 📓
