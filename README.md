# Sentiment Analysis Using Logistic Regression

This repository contains an implementation of a binary sentiment classification model using Logistic Regression. The model is trained to classify movie reviews as either positive or negative based on the Rotten Tomatoes dataset.

## Table of Contents
- [Dataset](#dataset)
- [Requirements](#requirements)

## Dataset

The dataset used for training the model consists of 5,331 positive and 5,331 negative movie reviews from the Rotten Tomatoes movie reviews dataset. The dataset can be found [here](https://www.cs.cornell.edu/people/pabo/movie-review-data/rt-polaritydata.README.1.0.txt).

The data is split into:
- **Training Set**: 4,000 positive and 4,000 negative reviews.
- **Validation Set**: 500 positive and 500 negative reviews.
- **Test Set**: 831 positive and 831 negative reviews.

## Requirements

This project uses the following Python libraries:
- `pandas`
- `scikit-learn`
- `nltk`

To install the required libraries, you can use:

```bash
pip install pandas scikit-learn nltk
```

The nltk library requires some additional datasets for tokenization and stopwords. These can be downloaded using:

```bash
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```
