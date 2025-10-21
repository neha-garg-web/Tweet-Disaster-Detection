# Tweet-Disaster-Detection

This project focuses on classifying whether a given tweet refers to a real disaster or not, using Natural Language Processing (NLP) techniques and a TensorFlow-based neural network.
The task helps automate the detection of disaster-related tweets to assist emergency response teams and improve situational awareness.

🔍 Overview

The goal of this project is to build a machine learning model that analyzes the text of tweets and predicts if they describe a real disaster (such as an earthquake, flood, or fire) or a non-disaster (such as metaphorical or irrelevant content).

The model is trained on the Kaggle “Real or Not? NLP with Disaster Tweets” dataset and demonstrates key steps in text preprocessing, tokenization, and deep learning for NLP.
Experimented with 8 different models to determine the best performer.
Utilized Naive Bayes, Dense Model, LSTM, GRU, Bidirectional-LSTM Model, 1D Convolutional Neural Network, Tensorflow Hub Pretrained Feature Extractor

**Key Features**

Dataset preprocessing and text cleaning

Tokenization and sequence padding using TensorFlow’s Tokenizer

Model built with Embedding, LSTM, and Dense layers

Binary classification: 1 → Real Disaster, 0 → Not a Disaster

Evaluation with accuracy and loss metrics

**Architecture**

Input Tweet Text
    ↓
Text Cleaning & Tokenization
    ↓
Embedding Layer
    ↓
LSTM / Bidirectional LSTM Layer
    ↓
Dense Layer with ReLU Activation
    ↓
Output Layer with Sigmoid Activation (Binary Output)
