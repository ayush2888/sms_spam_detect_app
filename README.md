# 📧 Spam Classifier Web App

A simple yet powerful web application that classifies SMS or Email messages as **Spam** or **Not Spam**, built using **Python**, **Streamlit**, and a **Machine Learning model** trained with `scikit-learn`.

---

## 🚀 Demo

https://smsspamdetectapp-aa5izfengmjrxl8dn8xjfy.streamlit.app/
---

## 🧠 How It Works

1. **Text Preprocessing**:  
   - Lowercasing  
   - Tokenization using `nltk`  
   - Removing stopwords and punctuation  
   - Stemming using `PorterStemmer`

2. **Vectorization**:  
   The cleaned text is transformed using a **TF-IDF vectorizer**.

3. **Prediction**:  
   A trained model (e.g., **Naive Bayes**, **Logistic Regression**, etc.) classifies the message as Spam or Not Spam.

---

## 📦 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt


##    Project Structure

spam-classification/
├── app.py                    # Streamlit app
├── model_spam_classification.pkl  # Trained ML model
├── vectorizer.pkl           # TF-IDF vectorizer
├── requirements.txt         # Python dependencies
└── README.md                # Project readme
