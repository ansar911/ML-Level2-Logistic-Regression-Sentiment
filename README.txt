# 🚀 Logistic Regression for Sentiment Analysis 

## 📌 Project Overview

This project focuses on building a Logistic Regression model to perform sentiment classification on textual data. The goal is to classify text into sentiment categories such as Positive, Negative, and Neutral.

---

## 🧠 Objective

* Convert raw text data into numerical form
* Train a classification model
* Evaluate model performance using standard metrics

---

## 📊 Dataset

* Sentiment Dataset (provided by Codveda)
* Contains text data along with sentiment labels

---

## 🧹 Data Preprocessing

* Removed unnecessary columns
* Selected relevant features: **Text** and **Sentiment**
* Simplified sentiment labels into:

  * Positive
  * Negative
  * Neutral

---

## 🔄 Feature Engineering

* Used **TF-IDF Vectorization** to convert text into numerical features

---

## 🤖 Model Used

* Logistic Regression (Scikit-learn)

---

## 📈 Model Evaluation

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score

### ✅ Result

* Achieved **~86% accuracy**
* Observed class imbalance affecting minority classes (Negative & Positive)

---

## ⚠️ Challenges Faced

* Dataset contained many fine-grained sentiment labels
* Converted them into broader categories for better performance
* Addressed class imbalance using `class_weight='balanced'`

---

## 🧠 Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorizer

---

## 🔗 Future Improvements

* Apply advanced NLP models (like Naive Bayes, SVM)
* Use deep learning (LSTM, BERT) for better accuracy
* Improve dataset balance

---


