# Sentiment Analysis for Food Product Reviews

## Overview
This project performs sentiment analysis on food product reviews using two different approaches:

1. **VADER (Valence Aware Dictionary and sentiment Reasoner)** - A lexicon-based, rule-based sentiment analysis tool optimized for social media text.
2. **Roberta Pretrained Model** - A transformer-based model from Hugging Face, leveraging deep learning to capture contextual sentiment nuances.

The project is implemented in Python and is designed to analyze customer reviews to determine their sentiment as positive, negative, or neutral.

## Features
- **Preprocessing of Text Data**: Tokenization, lowercasing, and stopword removal.
- **Sentiment Analysis using VADER**: Assigns polarity scores to text.
- **Sentiment Analysis using RoBERTa**: Uses a transformer-based model for classification.
- **Comparison of Both Methods**: Evaluates the performance of VADER and RoBERTa on real-world food product reviews.

## Installation
To run this project, ensure you have Python installed along with the required dependencies. You can install them using:

```bash
pip install transformers torch nltk vaderSentiment
```

## Usage
Run the notebook to perform sentiment analysis:

```bash
jupyter notebook sentiment_analysis_food.ipynb
```

## Data
The dataset consists of customer reviews of food products. The reviews undergo preprocessing before being fed into the sentiment analysis models.

## Results & Interpretation
- **VADER**: Works well for short, informal text but may struggle with context.
- **RoBERTa**: Provides more accurate predictions by considering the contextual meaning of words.


