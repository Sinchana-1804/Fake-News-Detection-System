# Fake News Detection System  

## 1. Overview  
This project focuses on building a machine learning model to classify news articles as fake or real using Natural Language Processing (NLP) techniques. The complete pipeline includes data preprocessing, exploratory data analysis (EDA), feature extraction, model training, evaluation, and prediction.

---

## 2. Dataset  
The project uses a labeled dataset of news articles containing textual content and corresponding labels:  

- text: News article content  
- label:  
  - 0 → Fake News  
  - 1 → Real News  

The dataset is preprocessed to remove noise and prepare text for modeling.

---

## 3. Project Stages  

### 3.1 Data Loading, Preprocessing & EDA  
- Loaded dataset from CSV file  
- Checked for missing values and duplicates  
- Cleaned text data (removal of punctuation, stopwords, etc.)  
- Performed text normalization  

Exploratory Data Analysis (EDA) included:  
- Distribution of fake vs real news  
- Text length analysis  
- Word frequency analysis  
- WordCloud visualization  
- N-gram analysis (bi-grams and tri-grams)  
- Statistical insights of text data  

---

### 3.2 Feature Engineering, Model Training & Evaluation  

**Feature Engineering**  
- Converted text into numerical features using TF-IDF Vectorization  
- Normalized feature representation  

**Model Training**  
- Logistic Regression  
- Naive Bayes  
- Passive Aggressive Classifier  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine (SVM)  
- XGBoost  

**Evaluation**  
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Cross-validation  

**Best Performing Model:** Logistic Regression  

---

### 3.3 Model Evaluation Plots  
- Confusion Matrix for best model  
- Model comparison bar chart  
- ROC curves for all models  
- Precision-Recall curve  
- Feature importance visualization  
- TF-IDF feature analysis  
- Radar chart for model comparison  
- Prediction confidence distribution  

---

## 4. Key Features  
- High-frequency words in fake vs real news  
- N-gram patterns  
- TF-IDF weighted keywords  

These features help differentiate linguistic patterns between fake and real news.

---

## 5. Prediction System  

### 5.1 Prediction on Sample Data  
- Predicts label (Fake/Real)  
- Displays confidence score  
- Shows probability distribution  

### 5.2 Prediction on New Input  
- Accepts custom news text  
- Predicts whether news is fake or real  
- Provides confidence level  

---

## 6. Saved Files  
- best_model_lr.pkl → Trained Logistic Regression model  
---

## 7. Conclusion  
The project demonstrates the use of NLP and machine learning techniques to detect fake news. Logistic Regression performed best and provided reliable classification results.

---

## 8. Future Improvements  
- Deploy as a web application  
- Integrate real-time news data  
- Use deep learning models (LSTM, BERT)  
- Expand dataset for better accuracy  