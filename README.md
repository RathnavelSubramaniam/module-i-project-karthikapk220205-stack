# 📈 Stock Market Sentiment Analysis using Word2Vec and Sentence Transformers

## 📌 Project Overview

This project focuses on predicting the sentiment of stock market news articles using Natural Language Processing (NLP) and Machine Learning/Deep Learning techniques. The project compares different text embedding methods and classification models to identify the most effective approach for sentiment classification.

The workflow includes data preprocessing, exploratory data analysis (EDA), text embedding generation, model training, evaluation, and performance comparison.

---

## 🎯 Objectives

- Analyze stock market news sentiment.
- Generate text embeddings using Word2Vec and Sentence Transformers.
- Train Machine Learning and Deep Learning models.
- Compare model performance using multiple evaluation metrics.
- Visualize data and model results.

---

## 📂 Project Workflow

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Word Embedding Generation
   - Word2Vec
   - Sentence Transformer (BAAI/bge-base-en-v1.5)
6. Model Building
   - Random Forest
   - Neural Network
7. Model Evaluation
8. Performance Comparison
9. Conclusion

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Correlation Matrix
- Stock Price Trend Analysis
- Price Distribution by Sentiment
- News Length Distribution
- Time Series Analysis
- Sentiment Distribution

---

## 🧠 Text Embedding Techniques

### Word2Vec

- Trained using Gensim
- Average Word Embeddings used as feature vectors

### Sentence Transformer

Model Used:

```
BAAI/bge-base-en-v1.5
```

Sentence embeddings are generated for every news article before classification.

---

## 🤖 Machine Learning Models

### Random Forest Classifier

Used with:

- Word2Vec Embeddings
- Sentence Transformer Embeddings

---

### Neural Network

Deep Learning model built using TensorFlow/Keras with:

- Dense Layers
- ReLU Activation
- Dropout Regularization
- Softmax Output Layer

---

## 📈 Model Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Performance comparison is performed for:

- Word2Vec + Random Forest
- Word2Vec + Neural Network
- Sentence Transformer + Random Forest
- Sentence Transformer + Neural Network

---

## 🛠️ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Gensim
- Sentence Transformers

---

## 📁 Repository Structure

```
Project/
│
├── Project_I_GenAI.ipynb
├── README.md
├── word2vec.model
└── dataset/
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### Install required packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow gensim sentence-transformers
```

### Run the notebook

```bash
jupyter notebook Project_I_GenAI.ipynb
```

---

## 📌 Key Features

- Complete NLP pipeline
- Data preprocessing
- Exploratory Data Analysis
- Word2Vec embeddings
- Sentence Transformer embeddings
- Random Forest classifier
- Neural Network classifier
- Model performance comparison
- Confusion Matrix visualization
- Stock market news sentiment classification

---

## 📚 Future Improvements

- Fine-tune Transformer models
- Hyperparameter optimization
- Deploy using Streamlit or Flask
- Real-time stock news prediction
- Use larger financial news datasets

---

## 👩‍💻 Author

**Karthika P**

---

## ⭐ If you found this project useful, consider giving it a Star
