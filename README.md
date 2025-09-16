# 🐦 Twitter Sentiment Analysis using LSTM

## 📌 Project Overview
This project implements a **Twitter sentiment analysis model** using **Long Short-Term Memory (LSTM)** networks.  
The model is trained on the **Sentiment140 dataset** to classify tweets as **positive, negative, or neutral**.  
Both **trainable and pre-trained Word2Vec embeddings** were explored to evaluate performance.  

---

## 🚀 Key Features
- **LSTM-based Sentiment Classifier**  
  Built and trained LSTM models for sequence-based sentiment prediction.  

- **Embedding Strategies**  
  - Trainable Word2Vec embeddings.  
  - Pre-trained Word2Vec embeddings (achieved better performance).  

- **Model Performance**  
  - **83.3% accuracy** with pre-trained embeddings.  
  - Improved generalization using **L2 regularization** and **dropout**.  

- **Custom Implementation**  
  Developed a **custom LSTM forward propagation** mechanism for optimized prediction, and benchmarked against standard LSTM inference.  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Frameworks & Libraries:** TensorFlow / PyTorch, NumPy, Pandas, Matplotlib  
- **Embeddings:** Trainable & Pre-trained Word2Vec  
- **Dataset:** [Sentiment140](http://help.sentiment140.com/for-students)  

---

## 📂 Project Structure
