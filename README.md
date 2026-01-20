# Spam Gmail Prediction 📧🚫

This project focuses on detecting spam emails in Gmail using machine learning and natural language processing (NLP). Spam detection is a critical application of text classification, helping email providers and users protect themselves from unwanted or malicious content.

---

## 📌 Project Overview
- Build a classification model to predict whether an email is **spam** or **ham** (not spam).
- Apply text preprocessing, feature engineering, and model evaluation.
- Integrate with Gmail data for real-world application.
- Deploy the model for interactive use.

---

## 🗂 Dataset
- Source: Public spam/ham email datasets (e.g., [Kaggle - Spam Email Dataset].
- Features:
  - **Email Text**: Subject + body of the email
  - **Label**: Spam or Ham (target variable)

---

## ⚙️ Methodology
1. **Data Cleaning & Preprocessing**  
   - Lowercasing, removing punctuation, stopwords  
   - Tokenization and lemmatization  
   - Handling imbalanced classes
2. **Feature Engineering**  
   - Bag of Words (BoW)  
   - TF-IDF vectorization  
   - N-grams (bigrams, trigrams)  
   - Custom stopword lists for Gmail-specific spam words
3. **Modeling**  
   - Naive Bayes Classifier  
   - Logistic Regression  
   - Random Forest 
4. **Evaluation**  
   Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC


---

## 📊 Results
- Compare models based on accuracy and robustness.
- Visualize confusion matrix and ROC curves.

---
