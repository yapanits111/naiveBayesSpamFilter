# Naive Bayes Spam Filter

A spam email classifier using the Naive Bayes algorithm on the TREC06 dataset.

## Features

- **Naive Bayes Classifier** with Laplace smoothing (lambda tuning)
- **Precision & Recall** evaluation across different lambda values
- **Word Cloud** visualization for spam and ham emails
- **Top Informative Words** extraction using log-likelihood ratio

## Dataset

Uses the **TREC06** email corpus with labeled spam/ham emails.

## Requirements

```
pandas
numpy
matplotlib
scikit-learn
wordcloud
```

## Usage

1. Upload the `trec06p-cs280.zip` dataset
2. Run all cells in `Naive_Bayes_Spam_filter.ipynb`
3. View precision/recall results and word cloud visualizations

## Results

Best performance achieved with λ = 0.005, optimizing the trade-off between precision and recall.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yapanits111/naiveBayesSpamFilter/blob/main/Naive_Bayes_Spam_filter.ipynb)