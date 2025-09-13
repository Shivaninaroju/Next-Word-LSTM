# 🧠 Next Word Prediction using LSTM (RNN):

A deep learning project to predict the next word in a sentence using an LSTM-based Recurrent Neural Network.

## 📌 Overview:

This project implements a Next Word Prediction model using a Long Short-Term Memory (LSTM) network built with TensorFlow/Keras. It demonstrates the principles of Natural Language Processing (NLP) and sequence modeling by predicting the next likely word based on a given input sequence.

Although not deployed, the primary goal of this project was to understand and implement sequence modeling using LSTMs.

## ✅ Objectives:

- Understand and build an LSTM-based Recurrent Neural Network.

- Preprocess text data for sequential modeling.

- Train and evaluate a word-level next word prediction model.

- Apply the model to predict text in the style of Shakespeare.

## 📚 Dataset:

The model was trained on Shakespeare's Hamlet from the Gutenberg Project. This classic English literature dataset offers rich and complex sentence structures, providing a challenging and insightful dataset for sequence prediction.

Text: The Tragedy of Hamlet, Prince of Denmark by William Shakespeare

## 🧪 Model Summary:

Parameter and Value
---
Model Type	            -    LSTM (RNN)

Layers	Embedding       -    → LSTM → Dense

Epochs	                -    50

Optimizer	            -    Adam

Loss Function           -    Categorical Crossentropy

Accuracy Achieved	    -    ~40%

Framework	             -   TensorFlow 2.15 + Keras

Python Version	         -   3.10.16

Note: The model can be improved with more epochs, better preprocessing, or fine-tuned architecture.

## ⚙️ Requirements:

Python 3.10.16

TensorFlow 2.15.0

NumPy

## 🧠 How It Works:

1. Text Preprocessing:

    Load Hamlet dataset

    Clean and tokenize the text

    Generate input sequences and targets

2. Model Architecture:

    Embedding layer to map tokens to vectors

    LSTM layer to capture sequential dependencies

    Dense layer with softmax for word prediction

3. Training:

    Trained for 50 epochs

    Loss: Categorical Crossentropy

    Optimizer: Adam

4. Prediction:

    Predicts next word for a given input string

5. 📈 Sample Output:

    Input: "To be or"

    Predicted Next Word: "not"

## 🧩 Future Improvements:

Increase training epochs and use callbacks

Expand to complete text generation

Experiment with Bidirectional LSTMs or attention mechanisms

Deploy the model with Flask or FastAPI

Improve dataset by cleaning stage directions, punctuation, etc.

## 🚀 Purpose:

This project was developed for educational purposes to gain practical experience in NLP, LSTM modeling, and deep learning workflows. The goal was implementation and understanding, not high accuracy.
