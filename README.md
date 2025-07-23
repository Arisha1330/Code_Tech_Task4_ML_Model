# Code_Tech_Task4_ML_Model

# 📧 SMS Spam Classifier - Machine Learning Project

This repository contains a machine learning model to classify SMS messages as **spam** or **ham** using **Scikit-learn**. This task is part of **CodTech Internship Task 4**.

## 🚀 Project Overview

The goal of this project is to build a spam classifier using the **SMS Spam Collection Dataset**. We use Natural Language Processing (NLP) techniques such as **CountVectorizer** and implement a **Naive Bayes** classifier to distinguish between spam and non-spam (ham) messages.

---

## 📁 Dataset

- Dataset used: [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
- Columns:
  - `label`: spam or ham
  - `message`: actual SMS text

---

## 🔧 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `sklearn` (scikit-learn)

---

## 🧠 Model Used

- **Multinomial Naive Bayes** (suitable for text classification)
- **CountVectorizer** for text feature extraction

---

## 📊 Model Evaluation

- **Accuracy**: ~97.84%
- **Precision, Recall, F1-score**: Calculated using `classification_report` and `confusion_matrix`.

---

## 🧪 Steps Performed

1. Load and explore dataset
2. Preprocess the text data
3. Vectorize text using CountVectorizer
4. Split into training and test sets
5. Train MultinomialNB model
6. Evaluate model performance

---

## 🖼️ Sample Output

```
Accuracy: 0.9784
Confusion Matrix:
[[965   0]
 [ 13 137]]
```

---

## 📂 How to Run

1. Clone the repo  
   `git clone https://github.com/yourusername/sms-spam-classifier.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Open Jupyter Notebook  
   `jupyter notebook ML_Model_Task4.ipynb`

---

## ✍️ Author

- **Arisha Ansari**  
- CodTech Internship – Task 4  
- July 2025

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
