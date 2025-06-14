# Basic_IMDB_Sentiment_Analysis
Using a dataset from Kaggle which contains reviews from 50K movies and their respective sentiments, I created a basic Logistic Regression model in Python and printed its accuracy score and classification report.
# 🎬 IMDb Movie Review Sentiment Analysis

This project is a basic sentiment analysis classifier built using a **Logistic Regression** model on the **IMDb movie review dataset**. The dataset consists of **50,000 reviews**, labeled as either positive or negative.

---

## 📊 Dataset

- **Source:** [IMDb Large Movie Review Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Size:** 50,000 labeled reviews (80:20 ratio for training and testing)
- **Labels:** 
  - `positive` → Positive  
  - `negative` → Negative

---

## 🚀 Objective

To build a binary text classifier using Logistic Regression that can determine the sentiment of a movie review.

---

## 🛠️ Technologies & Libraries

- Python 3.11.9
- `pandas` – Data handling
- `nltk` - for tokenizing 
- `scikit-learn / sklearn` – ML model, vectorization, Label Encoding, train/test split, Logistic Regression model, accuracy score and classification report

---

## 🧠 Model Used

- **Logistic Regression**: A simple yet effective linear model for binary classification.
- **TF-IDF Vectorizer**: Converts raw text into numerical feature vectors.

---

## 🧪 Workflow

1. **Load Dataset**
2. **Preprocess Text**
   - Lowercasing
   - Removing punctuation, stopwords, etc.
3. **Convert Text to Vectors**
   - Using TF-IDF
4. **Split Data**
   - Train/test split (e.g., 80/20)
5. **Train Model**
   - Logistic Regression using `sklearn`
6. **Evaluate Model**
   - Accuracy, Precision, Recall, F1-score

---

## 📈 Results

- **Accuracy:** *0.8961*  
- **F1-Score:** *0.90*  
- The model performs reasonably well for a baseline logistic regression classifier. Further improvements can be made by using more advanced models like SVM, Random Forest, or deep learning approaches (RNNs, BERT).

---

## 📂 Repository Structure

