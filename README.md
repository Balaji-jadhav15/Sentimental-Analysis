Sentiment Analysis on Restaurant Reviews

📌 Project Overview

This project performs sentiment analysis on restaurant reviews using Natural Language Processing (NLP) and Machine Learning (ML) techniques. The model classifies reviews as positive or negative based on textual data.

🚀 Features

Preprocessing of text using TF-IDF Vectorization

Sentiment classification using Multinomial Naive Bayes

Cross-validation for better model evaluation

Real-time sentiment prediction for user input

📂 Dataset

Source: Google Drive (TSV file format)

Columns:

Review: Contains the text of the review.

Liked: Sentiment label (1 = Positive, 0 = Negative).

🛠️ Technologies Used

Python (pandas, scikit-learn, gdown, numpy)

Machine Learning (Naive Bayes Classifier)

Text Processing (TF-IDF Vectorizer)

📜 Installation & Setup

1️⃣ Install Dependencies

Ensure you have the required libraries installed:
How It Works

Dataset Download: The script downloads the dataset from Google Drive.

Preprocessing: The reviews are cleaned and transformed into numerical features using TF-IDF.

Model Training: A Multinomial Naive Bayes classifier is trained using a train-test split.

Evaluation: Model performance is evaluated using cross-validation accuracy & classification reports.

User Input Prediction: The user can enter a review, and the model will predict its sentiment.



