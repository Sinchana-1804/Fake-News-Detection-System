Fake News Detection System
Overview

This project focuses on building a machine learning model to classify news articles as fake or real using Natural Language Processing (NLP) techniques. The complete pipeline includes data preprocessing, exploratory data analysis (EDA), feature extraction, model training, evaluation, and prediction.

Dataset

The project uses a labeled dataset of news articles containing textual content and corresponding labels:

text: News article content
label:
0 → Fake News
1 → Real News

The dataset is preprocessed to remove noise and prepare text for modeling.

Project Stages
1. Data Loading, Preprocessing & EDA
Loaded dataset from CSV file
Checked for missing values and duplicates
Cleaned text data (removal of punctuation, stopwords, etc.)
Performed basic text preprocessing and normalization

Exploratory Data Analysis (EDA) included:

Distribution of fake vs real news
Text length analysis
Word frequency analysis
WordCloud visualization for fake and real news
N-gram (bi-gram/trigram) analysis
Statistical insights of text data
2. Feature Engineering, Model Training & Evaluation
Feature Engineering
Converted text data into numerical features using TF-IDF Vectorization
Normalized feature representation
Model Training

Trained multiple classification models:

Logistic Regression
Naive Bayes
Passive Aggressive Classifier
Random Forest
Gradient Boosting
Support Vector Machine
XGBoost
Evaluation
Models evaluated using:
Accuracy
Precision
Recall
F1-score
Cross-validation

Best Performing Model: Logistic Regression achieved the highest performance among all models.

3. Model Evaluation Plots

Generated multiple visualizations for performance comparison:

Confusion Matrix for best model
Model comparison bar chart (accuracy and cross-validation scores)
ROC curves for all models
Precision-Recall curve
Feature importance visualization
TF-IDF feature analysis
Model performance radar chart
Prediction confidence distribution
4. Key Features

Important textual features contributing to classification include:

High-frequency words in fake vs real news
N-gram patterns
TF-IDF weighted keywords

These features help differentiate linguistic patterns between fake and real news.

5. Prediction System
Prediction on Sample Data
Model tested on sample news articles
Outputs include:
Predicted label (Fake/Real)
Confidence score
Probability distribution
Prediction on New Input
Users can input custom news text
System predicts whether the news is fake or real
Provides confidence level of prediction
Saved Files
best_model_lr.pkl → Trained Logistic Regression model
tfidf_vectorizer.pkl → TF-IDF feature transformer
Conclusion

The project successfully demonstrates the application of NLP and machine learning techniques to detect fake news. Logistic Regression performed best among the tested models, providing reliable classification results. The system can be extended into real-world applications such as news verification platforms.

Future Improvements
Deployment as a web application
Integration with real-time news APIs
Use of deep learning models (LSTM, BERT)
Larger and more diverse dataset

Author

* Sinchana Shanbhag 
* Vibha Shanbhag
* Chinmay Shanbhag


