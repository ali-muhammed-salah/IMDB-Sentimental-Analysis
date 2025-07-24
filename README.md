# 🎬 IMDb Sentiment Analysis – NLP Task

### 🚀 **ELEVVO Internship Project**

* 👤 **Author:** Ali Muhammed
* 📝 **Task Level:** NLP Task 1

---

## 🎯 **Objective**

Build a machine learning model to analyze **IMDb TV Show Reviews** and classify them as **positive ✅** or **negative ❌** using classic NLP techniques.

---

## 📁 **Dataset**

* **Dataset:** IMDb Reviews
* **File:** IMDB TV Shows.csv
* **Columns Used:**

  * `Rating (out of 10)` (Number)
  * `Review` (Text)
  * `Show ID` (Alphanumeric)
  * `Review ID` (Alphanumeric)

---

## 🛠 **Tools & Libraries**

Here is your **updated libraries list** with all the imported libraries from your code:

---

* 🐍 Python
* 📊 Pandas
* ✂️ NLTK
* 🔡 re (Regular Expressions)
* 🔢 NumPy
* 📈 Matplotlib (pyplot)
* ☁️ WordCloud
* 🤖 Scikit-learn

---

## 🔄 **Workflow Overview**

### 🛠️ **1. Data Cleaning & Preprocessing**

* 🔡 Converted all reviews to lowercase
* 🧹 Stripped out HTML tags and special characters
* 🚫 Removed stopwords using **NLTK stopword lists**

---

### ✨ **2. Feature Transformation**

* 🧮 Applied **TF-IDF Vectorizer** and **Count Vectorizer (Bonus)** to turn text data into numerical feature vectors for model training

---

### 🤖 **3. Model Building**

* 🔍 Used **Logistic Regression Model** and **Multinomial Naive Bayes Model (Bonus)** as the classification algorithms
* 🗂️ Split dataset into **80% training** and **20% testing**

---

### 📊 **4. Performance Evaluation**

* 🎯 Metrics: **Accuracy**, **Confusion Matrix** and **Classification Report**
---

Here is a **clear and structured description** of the two types of visualizations you created, ready for your README:

---

### 🎨 **Visualizations Created**

#### 1️⃣ **Bar Chart Visualizations**

* **What:** Plotted **horizontal bar charts** showing the **top distinctive words** for each sentiment class.
* **Details:**

  * Separate plots for **positive** and **negative** reviews.
  * Words ranked by their **average TF-IDF scores**.
* **Purpose:** Helps identify which words are **most strongly associated** with positive or negative sentiments in the dataset.

---

#### 2️⃣ **Word Frequency Analysis**

* **What:** Computed the **average TF-IDF frequency** of each word across all reviews by sentiment.
* **Details:**

  * Extracted **top 50 distinctive words** for both positive and negative classes.
  * Used these frequencies for visualization to highlight **important terms** in each category.
* **Purpose:** Provides insight into **common and impactful vocabulary** used in reviews, supporting sentiment interpretation and feature importance understanding.

---

## 🔎 **Sample Insights**

| Sentiment   | Top Words                       |
| ----------- | ------------------------------- |
| 😊 Positive | great, amazing, love, excellent |
| 😞 Negative | boring, bad, worst, terrible    |

---

Here is your **equivalent “Model Comparison” section** rewritten for your README, using your own task context and emojis:

---

## 📊 **Model Insights**

| **Model**                  | **Vectorizer** | **Accuracy**   |
| -------------------------- | -------------- | -------------- |
| 📈 **Logistic Regression** | TF-IDF         | \~87% ✅ |
| 🤖 **Naive Bayes**         | Count Vectorizer         | \~87% ✅       |

---

## 💡 **Key Learnings**

* Classical NLP preprocessing pipeline
* TF-IDF and Count Vectorizer feature engineering
* Logistic Regression and Naive Bayes classification
* Visualizing distinctive words by sentiment

---

> **Note:** This task focused on **classic NLP (no deep learning)** to strengthen fundamental understanding before moving to advanced transformer models.

