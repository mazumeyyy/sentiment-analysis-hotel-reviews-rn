# Sentiment Analysis of Hotel Reviews (RNN & LSTM)

This project builds and compares SimpleRNN and LSTM models for binary sentiment classification of hotel reviews.  
It covers data preprocessing, model training, evaluation on a held-out test set, and visualization of learning curves.

## Dataset

- Source: `data/Hotel_Reviews.csv` (1000 review subset)
- Target: Binary sentiment label (positive vs negative)

## Models

- SimpleRNN with trainable embedding
- LSTM with the same embedding and hidden units
- Both trained on the same splits and evaluated on the same test set

## Results (short summary)

- SimpleRNN test accuracy: ~74.6%
- LSTM test accuracy: ~74.6%

Both models achieve similar performance on the test set, with mild overfitting visible in the validation loss curves.

