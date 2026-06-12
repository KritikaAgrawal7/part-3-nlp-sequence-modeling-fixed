# NLP and Sequence Modeling Mini Project

## Project Overview

This project focuses on building an NLP pipeline for customer sentiment analysis using both traditional machine learning and sequence-based deep learning approaches.

The project includes:

- Text preprocessing

- TF-IDF vectorization

- Logistic Regression baseline model

- LSTM sequence model

- Sentiment classification evaluation

The objective was to understand how NLP text processing, vectorization, and sequence models work in sentiment analysis tasks.

---

## Dataset Information

The dataset contains customer support messages labeled into:

- Positive

- Negative

- Neutral

Dataset size:

- 1500 records

Features include:

- customer messages

- sentiment labels

- word counts

- urgency flags

---

## NLP Preprocessing Steps

The following preprocessing techniques were applied:

- Lowercasing

- Removing special characters

- Tokenization

- TF-IDF vectorization

- Sequence padding for LSTM

---

## Baseline Model

A Logistic Regression model was trained using TF-IDF features.

Evaluation metrics:

- Accuracy score

- Classification report

- Confusion matrix

The baseline model achieved excellent sentiment classification performance.

---

## LSTM Sequence Model

A sequence-based LSTM architecture was implemented using:

- Embedding layer

- LSTM layer

- Dense layers

- Softmax output layer

The LSTM model successfully learned sequential dependencies and contextual sentiment patterns from text.

---

## Attention and Transformer Reflection

RNNs struggle with long-term dependencies because earlier sequence information can fade during training.

LSTMs improve memory retention using gates and memory cells.

Attention mechanisms help models focus on important parts of a sequence.

Transformers use self-attention and parallel processing, making them highly effective for modern NLP and Generative AI applications.