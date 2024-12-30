# Financial Sentiment Analysis Project

This repository contains the sentiment and topic analysis of financial earnings call transcripts from HSBC and JP Morgan for the Bank of England. The project leverages state-of-the-art NLP techniques to derive actionable insights.

## Features
- **Data Preprocessing**: Cleaning and structuring raw transcripts.
- **Sentiment Analysis**: Using Phi-3.5 and FinBERT to classify sentiment trends.
- **Topic Modeling**: Identifying key themes using PCA, t-SNE, and KMeans clustering.

## Repository Structure
sentiment-analysis-project/
├── README.md
├── LICENSE
├── requirements.txt
├── data/
│   ├── raw/
│   ├── processed/
├── notebooks/
│   ├── data_preparation.ipynb
│   ├── sentiment_analysis.ipynb
│   ├── topic_modeling.ipynb
├── src/
│   ├── __init__.py
│   ├── data_preparation.py
│   ├── sentiment_analysis.py
│   ├── topic_modeling.py
├── results/
│   ├── visualizations/
│   ├── reports/
├── tests/
│   ├── test_data_preparation.py
│   ├── test_sentiment_analysis.py
├── .gitignore
└── CONTRIBUTING.md
