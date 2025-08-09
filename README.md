# E-commerce-Customer-Reviews-Sentiment-Analysis-using-TF-IDF-Logistic-Regression
## 📌 Overview
This project performs sentiment analysis on customer reviews from an e-commerce website.  
The goal is to classify reviews as **Positive**, **Neutral**, or **Negative** using **Natural Language Processing (NLP)** techniques and a **Logistic Regression** model.

## 📂 Dataset
- **Source:** Kaggle – Nykaa App Review Sentiment on #kaggle via @KaggleDatasets https://www.kaggle.com/datasets/nirant/nykaa-app-review-sentiment?utm_medium=social&utm_campaign=kaggle-dataset-share&utm_source=twitter. (Collect some reviews at random for analysis)
- **Description:** Text reviews along with manually assigned sentiment labels.

## 🛠 Steps in the Project
   
1. **Data Preprocessing**  
   - Removed numbers and punctuation  
   - Converted text to lowercase  
   - Removed stopwords  
   - Applied lemmatization using **WordNetLemmatizer**  

2. **Feature Extraction**  
   - Used **TF-IDF Vectorizer** to convert text into numerical features.  

3. **Model Selection & Training**  
   - Chose **Logistic Regression** classifier  
   - Trained on preprocessed TF-IDF features  

4. **Evaluation**  
   - Split dataset into train & test sets (85%-15%)  
   - Measured accuracy score for evaluation  

## 📊 Results
- **Accuracy:** ~ 75% 

