# Financial Sentiment Trend Prediction Tool

## 📘 Overview

This project explores whether financial news sentiment can serve as a predictive signal for short-term stock price movement, using Nvidia Corporation (NVDA) as a case study. By leveraging FinBERT — a transformer-based NLP model fine-tuned on financial text — the project extracts sentiment from news headlines and compares these predictions against actual market movement and human-annotated labels.

The tool was developed as part of a final-year undergraduate project in Data Science at the University of Westminster. The repository contains all source code, cleaned datasets, visualisations, and evaluation outputs

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
.
├── data/
│   ├── nvidia_news_raw.csv         # Raw headlines from NEWSAPI
│   ├── nvidia_news_labeled.csv     # Manually labeled subset of 30 headlines
│   ├── STOCK_US_XNAS_NVDA.csv      # Historical stock data from MarketWatch
├── Financial_Sentiment_Tool.ipynb  # Main analysis notebook
├── README.md                       # Project documentation


| Component              | Tool/Library                  | Purpose                                             |
| ---------------------- | ----------------------------- | --------------------------------------------------- |
| **Sentiment Analysis** | \[FinBERT (via Transformers)] | Classify headlines into positive, negative, neutral |
| **Data Analysis**      | pandas, numpy                 | Data wrangling, cleaning, aggregation               |
| **Visualization**      | matplotlib, seaborn           | Plot sentiment trends, confusion matrices           |
| **Data Sources**       | NEWSAPI, MarketWatch          | Real-world news and price data for Nvidia           |

News Headlines:
Collected using the NEWSAPI Python client.

Search term: "Nvidia"

Source types: Reputable financial and tech media outlets.

Period: ~3 weeks (April–May 2025)

Sample size: 106 headlines

2. Stock Prices:
Retrieved from MarketWatch (via CSV export)

Columns: Open, Close, High, Low, Volume

Matching date range with headline data.







