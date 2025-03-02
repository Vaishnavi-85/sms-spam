# SMS-Spam Detection
# Overview
SMS Spam Detection is a machine learning model that takes an SMS as input and predicts whether the message is a spam or not spam message. The model is built using Python and deployed on the web using Streamlit.

# Technology Used
Python
Scikit-learn
Pandas
NumPy
Streamlit

# Features
Data collection
Data cleaning and preprocessing
Exploratory Data Analysis
Model building and selection
Web deployment using Streamlit

# Data Collection
The SMS Spam Collection dataset was collected from Kaggle, which contains over 5,500 SMS messages labeled as either spam or not spam.

# Data Cleaning and Preprocessing

The data was cleaned by handling null and duplicate values, and the "type" column was label-encoded. The data was then preprocessed by converting the text into tokens, removing special characters, stop words and punctuation, and stemming the data. The data was also converted to lowercase before preprocessing.

# Exploratory Data Analysis

Exploratory Data Analysis was performed to gain insights into the dataset. The count of characters, words, and sentences was calculated for each message. The correlation between variables was also calculated, and visualizations were created using pyplots, bar charts, pie charts, 5 number summaries, and heatmaps. Word clouds were also created for spam and non-spam messages, and the most frequent words in spam texts were visualized.

# Model Building and Selection

Multiple classifier models were tried, including NaiveBayes, random forest, KNN, decision tree, logistic regression, ExtraTreesClassifier, and SVC. The best classifier was chosen based on precision, with a precision of 100% achieved.

# Web Deployment

The model was deployed on the web using Streamlit. The user interface has a simple input box where the user can input a message, and the model will predict whether it is spam or not spam.
