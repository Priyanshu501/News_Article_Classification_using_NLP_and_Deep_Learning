## Introduction

This project leverages Natural Language Processing (NLP) techniques and deep learning to classify news articles into different categories. The dataset used in the collection of news articles from BBC.

## Objective

The primary objective of this project is to develop a robust text classification model capable of accurately categorizing news articles. The project aims to demonstrate the practical appliation of NLP and deep learning in solving real-world text classification problems.

## Implementation

1. Data Collection and Preprocessing:

    * **Dataset**: The BBC dataset contains approximately 2000+ news articles across 5 categories.

    * **Pre-processing Steps**: 
        * Tokenization using Keras Tokenizer.
        * Padding sequences to a uniform length using Keras pad_sequences.
        * Encoding lables using scikit-learn's LabelEncoder.

2. Model Development:

    * Architecture:

        * **Embedding Layer**: Converts words into dense vectors of fixed size.
        * **LSTM Layer**: Long Short-Term Memory network to capture dependencies in text.
        * **Dense Layer**: Fully connected layer with softmax activation for classification.

    * Hyperparameters:

        * Vocabulary Size: 20,000
        * Sequence Length: 1,000
        * Embedding Dimension: 128
        * LSTM Units: 128

## Summary

This project showcases the practical application of NLP and deep learning in text classification, by developing a scalable, interpretable, and user-friendly solution.