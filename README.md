# 📌 SMS Fraud Classification in Indonesia using Machine Learning & Deep Learning

## 📖 Overview
This project investigates the classification of Indonesian SMS messages into **Fraud**, **Advertisement**, and **Normal** categories using various **machine learning** and **deep learning** models. The research evaluates the performance of models like **Hybrid CNN-LSTM, Naïve Bayes, Support Vector Machine (SVM), and IndoBERT embeddings**, with **ensemble learning** achieving the best results.

## 📊 Methodology
### 1. **Dataset**  
- Contains **1,143 Indonesian SMS** categorized into:
  - **569 Normal messages**
  - **335 Fraud messages**
  - **239 Advertisement messages**

### 2. **Preprocessing Steps**  
- Convert text to lowercase  
- Tokenization  
- Stopword removal  
- Stemming  

### 3. **Feature Extraction**  
- **IndoBERT Embeddings** for text representation.

### 4. **Models Used**
- **Hybrid CNN-LSTM**
- **Naïve Bayes**
- **Support Vector Machine (SVM)**
- **Stacking Ensemble Learning (CNN-LSTM + SVM + Naïve Bayes)**

### 5. **Evaluation Metrics**
- Accuracy
- Precision
- Recall
- F1-Score  

**Best Model:** Stacking Ensemble Learning with **94% accuracy, precision, recall, and F1-score**.

## 🏆 Results
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|----------|----------|--------|----------|
| Stacking Ensemble | **94.32%** | **94.64%** | **94.32%** | **94.42%** |
| Support Vector Machine | 94.32% | 94.66% | 94.32% | 94.42% |
| Naïve Bayes | 93.89% | 94.51% | 93.89% | 94.05% |
| Hybrid CNN-LSTM | 86.46% | 88.07% | 86.46% | 86.70% |

## 📌 Future Work
- Increase dataset size for better generalization.
- Experiment with **transformer-based models** like IndoBERT in an end-to-end setup.
- Deploy the model as a **real-time SMS fraud detection API**.
