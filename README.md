## Project Overview
This project implements a Spam Mail Detection System using Python. The system leverages machine learning techniques to classify emails as either spam (unwanted or fraudulent messages) or ham (legitimate messages). The classification model is trained using the Support Vector Machine (SVM) algorithm, which is known for its effectiveness in text classification tasks.

The model is built using the scikit-learn library and utilizes a bag-of-words approach to represent text data as numerical vectors. The project aims to demonstrate how machine learning can be applied to solve real-world problems, such as spam filtering in email systems.

## Features
## Data Loading: 
Loads email data from a CSV file (spam.csv), which contains labeled messages categorized as either "spam" or "ham."
## Text Preprocessing: 
Uses CountVectorizer to convert text data into a format suitable for machine learning.
## Model Training: 
Trains a Support Vector Machine (SVM) model to classify emails as spam or ham.
## Model Evaluation: 
Evaluates the model using metrics such as accuracy, precision, recall, and F1 score to measure its performance.
## Real-Time Predictions: 
Enables the user to test new messages for spam classification.
## Technologies Used:
Python: Programming language used to implement the spam detection system.
Libraries:
pandas: For data manipulation and cleaning.
scikit-learn: For machine learning algorithms and text processing.
CountVectorizer: For converting text into a numerical format.
SVM (Support Vector Machine): A machine learning model used for classification.
## Dataset:
The dataset used in this project is the Spam SMS dataset sourced from Kaggle. The dataset is labeled with two categories: spam and ham (legitimate messages). The data was originally provided by Anagha K P.

## Data Source: 
Kaggle - Spam SMS Dataset
## Columns:
v1: The label (spam or ham).

v2: The message text.
