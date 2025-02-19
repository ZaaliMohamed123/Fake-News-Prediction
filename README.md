# **Fake News Prediction Project**

**Project Description**

This project involves developing a machine learning model to predict whether a news article is fake or real. The dataset used for this project is sourced from a Kaggle competition, which includes news articles labeled as reliable or unreliable. The goal is to preprocess the text data, convert it into numerical features, train a logistic regression model, and evaluate its performance.

**Steps and Methodology**

1.	Data Collection and Preprocessing:
 *	Load the dataset using pandas.
 * Handle missing values .
 *	Merge the author, title, and text columns into a single content column for feature engineering.
2.	Text Preprocessing:
 * Apply stemming to reduce words to their root forms using the Porter Stemmer.
 *	Remove stopwords and non-alphabetic characters to clean the text data.
3.	Feature Extraction:
 * 	Convert the preprocessed text data into numerical features using TF-IDF Vectorization.
4.	Model Training:
 * 	Split the dataset into training and testing sets.
 *	Train a logistic regression model on the training data.
5.	Model Evaluation:
 *	Evaluate the model's performance using accuracy scores on both training and test data.
6.	Predictive System:
 *	Implement a function to predict the label of new news articles based on the trained model.

**Link to dataset** : https://www.kaggle.com/competitions/fake-news/data?select=train.csv

