# RNN - Sentiment Analysis on IMDB Movie Reviews

This repository implements a sentiment analysis model using a Recurrent Neural Network (RNN) for the IMDB movie reviews dataset. The model leverages PyTorch and pre-trained GloVe embeddings for accurate predictions.

---

## Overview

Sentiment analysis is a natural language processing task that classifies text data as positive or negative. This project uses:
- **Dataset**: IMDB movie reviews from `torchtext.datasets.IMDB`
- **Model**: RNN with GRU layers and GloVe embeddings
- **Framework**: PyTorch

The model processes tokenized movie reviews, builds vocabulary, and trains a neural network to classify reviews with high accuracy.

---

## Features

- Pre-trained GloVe embeddings for semantic understanding.
- GRU-based RNN for sequential text data processing.
- Visualization of training metrics and sentiment predictions.
- Easy-to-use prediction function for new sentences.

---

## Installation

### Prerequisites
- Python 3.8+
- PyTorch 2.0.1+cu118
- TorchText 0.15.2
- NumPy 1.24.4
- Matplotlib
- PortaLocker 2.0.0+
- Spacy with en_core_web_sm
- GPU (optional but recommended)

---

## Results

### Training Metrics

The model achieved 88.15% validation accuracy after 20 epochs. Loss and accuracy plots show consistent improvements over epochs.

Below are the loss and accuracy trends:

### Example Predictions

| Review                                                              | Prediction |
|---------------------------------------------------------------------|------------|
| "The plot was engaging and the characters were well-written."       | Positive   |
| "I couldn't sit through the entire movie; it was that boring."      | Negative   |
| "Absolutely loved it! The visuals were stunning."                   | Positive   |

---

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.
