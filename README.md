# Sentiment Analysis for Bank Customer Feedback

A sentiment analysis system that processes customer feedback using both traditional machine learning and transformer-based approaches. The project demonstrates the effectiveness of domain-specific feature engineering.

## Project Overview

This project implements a sentiment analysis solution that achieved 97% accuracy using a scikit-learn approach, significantly outperforming a transformer-based model (61% accuracy).

## Key Features

- **Dual Model Approach**: Implements both scikit-learn (Logistic Regression) and transformer-based models
- **Advanced Feature Engineering**: Combines TF-IDF vectorization with lexical features
- **High Accuracy**: 97% accuracy on customer feedback classification

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ghsaberr/sentiment-analysis-customer-feedback
cd sentiment-analysis-customer-feedback
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Download required NLTK data:
```bash
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords'); nltk.download('wordnet')"
```

## Model Performance

- **Scikit-learn Model**: 97% accuracy
- **Transformer Model**: 61% accuracy
- Dataset distribution:
  - Positive: 687 samples
  - Neutral: 136 samples
  - Negative: 177 samples