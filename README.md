# Emotion Analysis from Text 

This repository contains a Jupyter Notebook. The project applies Natural Language Processing (NLP) techniques to detect and classify emotions from raw text using machine learning.

---

## 💡 Project Objective

Build a machine learning model capable of classifying text into predefined emotion categories using real-world data from social platforms. This helps automate emotion detection in customer feedback, social monitoring, and mental health analysis.

---

## 📦 Dataset Used

- **Source**: [Kaggle – Emotion Analysis Based on Text](https://www.kaggle.com/datasets/simaanjali/emotion-analysis-based-on-text)
- Due to size limitations, a subset of the dataset was used for this analysis.
- The dataset includes text samples labeled with different emotions (e.g., joy, anger, sadness, etc.)

---

## 📈 Workflow Overview

1. **Data Collection**  
   - Extracted from Kaggle, containing emotion-labeled text.

2. **Data Preprocessing**  
   - Removed punctuation, stopwords, and special characters
   - Normalized case and removed irrelevant tokens

3. **Feature Extraction**  
   - Applied TF-IDF vectorization to transform text into numerical features

4. **Model Training**  
   - Used Logistic Regression to classify text based on emotional tone

5. **Model Evaluation**  
   - Accuracy, F1-score, confusion matrix, and classification report

6. **Prediction**  
   - Tested model on unseen/custom text inputs to demonstrate generalization

---

## 🛠 Tools & Libraries

- `pandas`, `numpy`, `matplotlib`
- `nltk` for text preprocessing
- `scikit-learn` for modeling and evaluation

---

## 🧠 Key Outcomes

- Successfully classified text samples into emotional categories
- Built an end-to-end machine learning pipeline for NLP tasks
- Demonstrated real-world applications of emotion classification

---

## 👤 Author

**Ashwani Kumar**  
AI and Data Science Student

---

## 📜 License

This project is intended for academic and personal portfolio use only.
