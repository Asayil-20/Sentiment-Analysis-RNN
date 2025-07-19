# 🎬 Sentiment Analysis with RNN-based Models

This project uses deep learning to classify the sentiment of movie reviews (positive or negative) using the IMDb dataset. It compares multiple RNN-based architectures to evaluate which model performs best in natural language understanding.

## 🧠 What Does This Project Do?

We built and trained several neural network models using TensorFlow/Keras, including:
- Simple RNN
- LSTM
- GRU
- Bidirectional LSTM
- CNN + LSTM

Each model was evaluated on its ability to correctly classify movie reviews based on their text content.

## 📊 Example Results
SimpleRNN Accuracy: 78.5%
LSTM Accuracy: 84.3%
GRU Accuracy: 85.1%
Bidirectional LSTM Accuracy: 86.0%
CNN+LSTM Accuracy: 85.7%


## 📁 Dataset

IMDb Movie Reviews Dataset  
🔗 [Kaggle Link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

Each review in the dataset is labeled as either `positive` or `negative`.

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
2.Open the notebook:

    Sentiment Analysis with RNN-based Models.ipynb using Jupyter Notebook or Google Colab.

Run all cells to:

    Preprocess data

    Train and evaluate models

    Predict sentiment for any custom review
