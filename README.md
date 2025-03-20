# Amazon Fine Food Review Sentiment Analyzer 🔍

A comparative analysis of sentiment detection using **NLTK VADER** and **Twitter RoBERTa** models on Amazon food reviews.

## 📌 Overview
This project implements and compares two sentiment analysis approaches:
- **VADER**: Rule-based sentiment analysis optimized for social media
- **RoBERTa-base**: State-of-the-art transformer model fine-tuned on Twitter data

Designed to showcase traditional NLP vs. modern deep learning performance on product review classification.

## 🚀 Features
- **Data Pipeline**:
  - Handles 500k+ reviews from Amazon Fine Food dataset
  - Converts 1-5 star ratings to binary sentiment (Positive/Negative)
  - Text cleaning and preprocessing
- **Dual Model Architecture**:
  - NLTK's VADER SentimentIntensityAnalyzer
  - Hugging Face Transformers pipeline with `cardiffnlp/twitter-roberta-base-sentiment`
- **Evaluation Suite**:
  - Accuracy & F1-Score metrics
  - Confusion matrix visualization
  - Comparative performance analysis

## 📁 Dataset
**Amazon Fine Food Reviews** (568,454 reviews)  
Source: [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews)

**Preprocessing**:
1. Filtered 1-2 star (Negative) and 4-5 star (Positive) reviews
2. Removed neutral 3-star reviews
3. Cleaned text
   

