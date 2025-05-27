# SentimentAnalysis-AmazonProductReview
Make Sentiment Analysis on Amazon Product review Using TF-IDF Vectorizer and Logistic Regression

his project performs sentiment analysis on Amazon product reviews.


- Data Loading and Preprocessing:

The dataset is downloaded from Kaggle using kagglehub.
The dataset is loaded into a pandas DataFrame.
Missing values are handled by dropping rows with nulls.
Review headlines and body are combined into a single column.
A cleaning function is applied to the combined text to lowercase, remove HTML tags, special characters, and extra spaces.
Stopwords are removed from the cleaned text.


- Model Training and Evaluation:


The data is split into training and testing sets.
A pipeline is created using TfidfVectorizer for feature extraction and LogisticRegression for classification.
The model is trained on the training data.
Predictions are made on the test data.
The model's performance is evaluated using accuracy, classification report, and confusion matrix.
A confusion matrix plot is generated.

Confusion Matrix of Model Evalution:

![Image](https://github.com/user-attachments/assets/a1465374-324d-4373-8d8b-83c19770bdca)
