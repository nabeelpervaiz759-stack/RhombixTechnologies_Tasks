# 📰 Fake News Detection System

## 📌 Overview
This project is a Machine Learning-based Fake News Detection System developed during my internship at Rhombix Technologies.

The system classifies news articles as Real or Fake using Natural Language Processing (NLP) techniques and Logistic Regression.

The model achieved 98% accuracy on the test dataset.

---

## 🎯 Problem Statement
With the rapid spread of misinformation online, it is important to automatically detect fake news.
This project builds a classification model that predicts whether a news article is genuine or fake based on its textual content.

---

## 📊 Dataset
The dataset contains labeled news articles:

- Fake News → Label 0
- Real News → Label 1

Each record includes:
- Title
- Article Text
- Label

For better feature representation, the title and article text were combined into a single feature.

---

## ⚙ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Pickle
- Gradio

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing
- Combined title + article text
- Removed stopwords
- Applied TF-IDF vectorization

### 2️⃣ Feature Engineering
TF-IDF Vectorizer settings:
- stop_words = 'english'
- ngram_range = (1,2)
- max_df = 0.7

### 3️⃣ Model Training
- Algorithm: Logistic Regression
- max_iter = 1000
- Train-Test Split: 80% / 20%

### 4️⃣ Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📈 Results
- Accuracy: 98%
- High precision and recall
- Minimal false positives and false negatives

---

## 💻 User Interface
An interactive web interface was built using Gradio.

Users can:
- Enter a news headline or article
- Get instant prediction (Real or Fake)

---

## 🚀 How to Run the Project

1. Install dependencies:
pip install -r requirements.txt

2. Run the application:
The Gradio interface will launch in your browser.

---

## 👨‍💻 Author
Muhammad Nabeel  
Data Science Student  
Intern at Rhombix Technologies
