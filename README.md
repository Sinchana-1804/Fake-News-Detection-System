Fake News Detection System

Project Overview

This project focuses on building a **Machine Learning model** to classify news articles as **Fake or Real** using Natural Language Processing (NLP) techniques.

The system processes textual data, extracts meaningful features, and applies multiple classification algorithms to achieve high accuracy.

---

Objectives

* Detect fake news using machine learning
* Apply NLP techniques for text preprocessing
* Compare multiple ML models
* Visualize insights using graphs and charts

---

Dataset

* File: `fake_news_dataset.csv`
* Contains news articles labeled as:

  * **0 → Fake News**
  * **1 → Real News**

---

Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* NLTK
* Matplotlib & Seaborn
* WordCloud
* XGBoost

---

Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Text Tokenization & Stopword Removal
4. Feature Extraction (TF-IDF)
5. Model Training
6. Model Evaluation
7. Visualization

---

Models Used

* Logistic Regression (Best Model)
* Naive Bayes
* Passive Aggressive Classifier
* Random Forest
* Gradient Boosting
* XGBoost
* Support Vector Machine

---

Best Model

* Logistic Regression

---

Results & Visualizations

Class Distribution

![Distribution](fig1_distribution.png)

WordCloud

![WordCloud](fig3_wordclouds.png)

Model Comparison

![Model Comparison](fig7_model_comparison.png)

Confusion Matrix

![Confusion Matrix](fig9_confusion_matrices.png)

ROC Curve

![ROC](fig10_roc_curves.png)

---

Saved Files

* `best_model_lr.pkl` → Trained model


---

How to Run

1. Clone the repository
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud xgboost
```

3. Run the notebook:

```bash
jupyter notebook
```

---

Future Improvements

* Deploy as a web application
* Use Deep Learning (LSTM, BERT)
* Improve dataset size and quality

---

Author

* Sinchana Shanbhag 
* Vibha Shanbhag
* Chinmay Shanbhag

---
