# Next Word Predictor using BiLSTM (PyTorch)

This project implements a **Next Word Prediction** model using **Bidirectional Long Short-Term Memory (BiLSTM)** in **PyTorch**. The model is trained on a dataset of Medium article titles to predict the next word in a given sentence.

## Dataset

The dataset used is the **[Medium Articles Dataset](https://www.kaggle.com/datasets/dorianlazar/medium-articles-dataset/data)** from Kaggle, containing article titles. The data is preprocessed using **NLTK tokenization**.

## Installation

Ensure you have Python 3.x installed. Then, install the necessary dependencies:

```bash
pip install torch torchvision nltk pandas numpy
```

## Model Architecture

- **Embedding Layer**: Converts words into dense vector representations.
- **BiLSTM Layer**: Captures long-term dependencies in both forward and backward directions.
- **Fully Connected Layer**: Outputs the probability distribution of the next word.

## Results

The model achieves reasonable accuracy on predicting the next word given an input phrase. 
## Author
Name: Anshul Katiyar
