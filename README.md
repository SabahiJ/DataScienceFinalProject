# Financial Sentiment Trend Prediction Tool

## 📘 Overview

This project explores whether financial news sentiment can serve as a predictive signal for short-term stock price movement, using Nvidia Corporation (NVDA) as a case study. By leveraging FinBERT — a transformer-based NLP model fine-tuned on financial text — the project extracts sentiment from news headlines and compares these predictions against actual market movement and human-annotated labels.

The tool was developed as part of a final-year undergraduate project in Data Science at the University of Westminster. The repository contains all source code, cleaned datasets, visualisations, and evaluation outputs in accordance with the data science lifecycle.

---

## 🎯 Objectives

- Collect sentiment-relevant news headlines about Nvidia using NewsAPI
- Clean and preprocess financial headlines for NLP analysis
- Apply FinBERT to classify sentiment as bullish, bearish, or neutral
- Merge sentiment data with stock price data to evaluate prediction accuracy
- Manually label a sample of headlines to benchmark FinBERT’s performance
- Generate visual insights and evaluate both model and real-world alignment

---

## 📂 Repository Structure

📁 data/
├── nvidia_news_raw.csv
├── nvidia_news_sentiment_labeled.csv
├── nvidia_news_labeled_.csv
├── nvidia_sentiment_vs_market.csv
└── Download Data - STOCK_US_XNAS_NVDA.csv

📁 notebooks/
└── Data_Science_Final_Project_Financial_Sentiment_Tool.ipynb
