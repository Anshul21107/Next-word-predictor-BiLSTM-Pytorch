# Next Word Predictor using BiLSTM (PyTorch)

![PyTorch](https://img.shields.io/badge/PyTorch-1.12-red.svg)

## 📌 Overview  
This repository contains the implementation of a **Next Word Prediction** model using **Bidirectional Long Short-Term Memory (BiLSTM)** in **PyTorch**. The model is trained on a dataset of Medium article titles to predict the next word in a given sentence.

## 📂 Dataset  
The dataset used is the **[Medium Articles Dataset](https://www.kaggle.com/datasets)** from Kaggle, containing article titles. The data is preprocessed using **NLTK tokenization**.

## 🔧 Installation & Dependencies  
To set up the project locally, follow these steps:

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/Next-word-predictor-BiLSTM-pytorch.git
cd Next-word-predictor-BiLSTM-pytorch
```

## 📊 Model Architecture  
- **Embedding Layer**: Converts words into dense vector representations.
- **BiLSTM Layer**: Captures long-term dependencies in both forward and backward directions.
- **Fully Connected Layer**: Outputs the probability distribution of the next word.

## 📈 Results  
The model achieves reasonable accuracy on predicting the next word given an input phrase. More evaluation metrics and fine-tuning results will be added.

## 👤 Author  
**Anshul Katiyar**  
GitHub: [Anshul21107](https://github.com/Anshul21107)  
LinkedIn: [Anshul Katiyar](https://www.linkedin.com/in/anshul-katiyar-430b23235/)  

---

