# Financial Sentiment Trend Prediction Tool

Overview

This project investigates the use of Natural Language Processing (NLP) and financial news sentiment analysis to predict short-term stock market trends for Nvidia Corporation (NVDA). The primary aim is to determine whether sentiment extracted from financial headlines can serve as a leading indicator of market direction. The study utilises FinBERT, a transformer-based language model trained on financial text, to classify sentiment which is then compared against real-world price movements and manually labeled evaluations.

The repository includes all components of the data science pipeline, including data collection, sentiment analysis, market data integration, model evaluation, and a comprehensive set of visualisations. This work was developed as part of the final year BSc Data Science programme.

Objectives

Collect and clean financial news data related to Nvidia (NVDA)

Apply FinBERT to classify headline sentiment (positive, neutral, negative)

Merge sentiment data with stock market prices (open/close)

Evaluate FinBERT’s accuracy using both manual labels and price direction

Present insights using structured data visualisation and analysis

Project Structure

data/
• nvidia_news_raw.csv
• nvidia_news_sentiment_labeled.csv
• nvidia_news_labeled_.csv
• nvidia_sentiment_vs_market.csv
• Download Data - STOCK_US_XNAS_NVDA.csv

notebooks/
• Financial_Sentiment_Tool.ipynb

visuals/ (optional)
• Exported PNGs of key visualisations

README.md
requirements.txt
LICENSE (optional)
.gitignore

Technologies and Methods

FinBERT language model (via HuggingFace Transformers)

Text pre-processing and cleaning (rule-based filters)

Sentiment scoring and confidence extraction

Manual validation and classification report metrics

Nasdaq price data (YFinance and alternate source)

Accuracy, precision, recall, F1-score, and signal alignment analysis

Visualisation with Matplotlib, Seaborn, WordCloud

Key Results

FinBERT classification accuracy vs. manual labels: 76.7%

FinBERT sentiment alignment with market direction: 42.86%

Key insight: While sentiment can provide useful signals, it is not sufficient alone to predict short-term market movement and should be used in conjunction with other indicators.
