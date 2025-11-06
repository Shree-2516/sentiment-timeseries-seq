# Sequence Deep Learning Showcase

Two sequence-based projects demonstrating LSTM and GRU on text and time-series data.

## Projects

### 1. Sentiment Analysis with LSTM
- Dataset: IMDB reviews (binary sentiment).
- Architecture: Embedding → LSTM → Dense (sigmoid).
- Achieved: ~85% accuracy.
- Files: `notebooks/01_sentiment_lstm.ipynb`, `src/sentiment/`

### 2. Time-Series Forecasting with GRU
- Task: Predict next values of a sine wave sequence.
- Architecture: GRU-based sequence model.
- Files: `notebooks/02_timeseries_gru.ipynb`, `src/timeseries/`

## Repo structure
See `/notebooks` for interactive exploration and `/src` for reusable modules (dataset, model, train).

## Quick start (local)
1. Clone repo:
   ```bash
   git clone https://github.com/<your-username>/seq-deep-learning-showcase.git
   cd seq-deep-learning-showcase
