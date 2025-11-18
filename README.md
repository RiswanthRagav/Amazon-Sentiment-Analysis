# Amazon-Sentiment-Analysis

## Project Overview
This project focuses on sentiment analysis of Amazon product reviews. Using machine learning techniques, we clean and preprocess review texts, explore patterns, build predictive models, and deploy a dashboard for real-time sentiment classification.

## Objectives
1. **Load and Explore Dataset**  
   - Import Amazon Reviews dataset (train & test).  
   - Understand dataset structure, column names, missing values, and basic statistics.  

2. **Clean and Preprocess Text**  
   - Lowercase text, remove punctuation, URLs, and extra spaces.  
   - Remove standard and custom stopwords.  
   - Prepare cleaned text for feature extraction.  

3. **Visualize Patterns and Distributions**  
   - Explore class distribution (positive vs negative reviews).  
   - Analyze review length distribution.  
   - Generate word clouds for positive and negative reviews.  
   - Identify top frequent words before and after stopword removal.  

4. **Build Machine Learning Models**  
   - Train models such as Logistic Regression, Naive Bayes, SVM, Random Forest, and XGBoost.  
   - Use TF-IDF vectorization for feature extraction.  
   - Evaluate models using accuracy, precision, recall, and F1-score.  
   - Compare models and select the best-performing one.  

5. **Evaluate and Interpret Results**  
   - Provide detailed metrics and plots for model comparison.  
   - Analyze the impact of preprocessing steps on model performance.  
   - Discuss insights gained from top frequent words and review lengths.  

6. **Deploy Streamlit Dashboard** *(In Progress)*  
   - Build a user-friendly dashboard for sentiment prediction.  
   - Allow users to input their review text and get real-time sentiment classification.  

