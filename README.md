# Text Emotion Classification Using Bidirectional GRU

## Overview

This project uses a Bidirectional Gated Recurrent Unit (BiGRU) neural network to classify emotions expressed in text.

## Technologies

- Python
- TensorFlow / Keras
- NumPy and Pandas
- Hugging Face Datasets
- Natural Language Processing (NLP)

## Model Architecture

The model uses an embedding layer followed by three bidirectional GRU layers, dropout layers, and a softmax output layer.

## Dataset

The project uses the `dair-ai/emotion` dataset from Hugging Face to classify text into six emotion categories:

- Sadness
- Joy
- Love
- Anger
- Fear
- Surprise

## Files

- `Sentiment_emotion_anylysis.ipynb` — notebook containing the model development and training workflow.
- `Bidirectional_GRU_model.keras` — trained model file. *(Update this name if your actual filename differs.)*
- `tokenizer.pkl` — saved tokenizer used to preprocess text.

## Current Progress

- [x] Dataset loading and preprocessing
- [x] Tokenization and sequence padding
- [x] Bidirectional GRU model training
- [x] Model and tokenizer saved
- [ ] Separate validation and final test evaluation
- [ ] FastAPI prediction endpoint
- [ ] Frontend interface
- [ ] MLOps integration

## Project Status

The model training and saving stage is complete. API development, frontend integration, and MLOps improvements are planned next.

## Author

Farhan Imran

GitHub: https://github.com/Mfarhanimran
