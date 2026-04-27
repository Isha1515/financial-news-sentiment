# Financial News Sentiment Analyser

## Overview
An NLP pipeline that analyses financial news headlines using FinBERT,
a BERT-based model trained specifically on financial text. Sentiment
scores are linked to real stock price data for AAPL, TSLA and MSFT.

## Tools Used
- Python, HuggingFace Transformers, FinBERT, yFinance, Pandas, Matplotlib

## Key Features
- Classifies headlines as positive, negative or neutral
- Visualises sentiment distribution per stock
- Links daily sentiment scores to real market data

## How to Run
1. Clone this repo
2. pip install -r requirements.txt
3. Open notebooks/sentiment_analysis.ipynb in Jupyter