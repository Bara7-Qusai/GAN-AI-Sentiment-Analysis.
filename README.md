# Sentiment Analysis using BERT

This project demonstrates how to use a pre-trained BERT model for sentiment analysis. The model predicts whether a given input text has a positive or negative sentiment.

## Model
We use the `textattack/bert-base-uncased-imdb` pre-trained model from the Hugging Face Transformers library. This model is fine-tuned on the IMDB dataset for binary sentiment classification.

## Requirements
To run this code, you need the following dependencies:

- `transformers` library by Hugging Face
- `torch` library for PyTorch

You can install the required libraries using pip:
```bash
pip install transformers torch
```
