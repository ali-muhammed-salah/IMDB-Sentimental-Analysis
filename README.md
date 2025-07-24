# 📝 IMDb Sentiment Analysis – NLP Task

### 🚀 **ELEVVO Internship Project**

**Author:** Ali Muhammed
**Task Level:** NLP Task 1 ✅

---

## 🎯 **Objective**

Develop a **Sentiment Analysis model** to classify **IMDb movie reviews** as **Positive** or **Negative** using traditional NLP and machine learning techniques.

---

## 📁 **Dataset Details**

* **Dataset:** IMDb Reviews
* **File:** IMDB Dataset.csv
* **Columns Used:**

  * `review` (text)
  * `sentiment` (positive/negative)

---

## 🛠️ **Tools & Libraries**

* Python 🐍
* Pandas 📊
* NLTK ✂️
* Scikit-learn 🤖
* cudf ⚡ (GPU acceleration)

---

## 🔗 **Workflow Overview**

1. **Data Cleaning & Preprocessing**

   * Lowercasing text 🔡
   * Removing HTML tags and punctuation ❌
   * Removing stopwords using NLTK 🛑

2. **Feature Extraction**

   * Converting text to numerical features using **TF-IDF Vectorizer**

3. **Model Training**

   * Algorithm: **Multinomial Naive Bayes**
   * Data Split: 80% train / 20% test

4. **Evaluation**

   * **Accuracy:** \~50% (baseline, before optimization)

5. **Visualization**

   * Bar charts showing **top distinctive words** in positive vs negative reviews

---

## 📊 **Sample Insights**

| Sentiment   | Top Words                       |
| ----------- | ------------------------------- |
| 😊 Positive | great, amazing, love, excellent |
| 😞 Negative | boring, bad, worst, terrible    |

---

## 💡 **Key Learnings**

* Classical NLP preprocessing pipeline
* TF-IDF feature engineering
* Naive Bayes classification
* Visualizing distinctive words by sentiment

---

## ✅ **Next Steps**

* Hyperparameter tuning for improved accuracy
* Trying different models (e.g. Logistic Regression, SVM)
* Deploying as an API for real-time inference

---

> **Note:** This task focused on **classic NLP (no deep learning)** to strengthen fundamental understanding before moving to advanced transformer models.

---

Let me know if you want a **version with emoji headers only** or a **fully minimal version** for your final internship submission today.
