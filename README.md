# Emotion Classification using Machine Learning

## Description
This project implements emotion classification using text data with machine learning models, specifically Naive Bayes and Support Vector Machine (SVM). The goal is to classify textual data into predefined emotional categories.

## Dataset
The dataset consists of text samples labeled with corresponding emotions. The text data is preprocessed, vectorized, and split into training and testing sets for model evaluation.

## Key Components
1. **Loading and Preprocessing**: 
   - Text cleaning, tokenization, and removal of stopwords.
   - Target labels are encoded into numerical format.

2. **Feature Extraction**: 
   - Utilized `TfidfVectorizer` to convert text data into numerical features.

3. **Model Development**: 
   - Trained two models: Naive Bayes and Support Vector Machine (SVM).

4. **Model Comparison**: 
   - Evaluated models using accuracy and F1-score metrics.
   - Generated classification reports for detailed performance analysis.

## Installation
To run this project, you need to have Python and the required libraries installed. You can install the required libraries using pip:

```bash
pip install pandas scikit-learn
