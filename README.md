# Phishing Email Detection Model

## Overview

The Phishing Email Detection Model is a machine learning-based cybersecurity project developed using Python and Scikit-learn. The system analyzes email content and classifies emails as either **Phishing** or **Safe**.

## Features

* Train on phishing and legitimate email datasets
* Text feature extraction using TF-IDF
* Email classification using Naive Bayes
* Accuracy evaluation
* Confusion Matrix visualization
* Real-time email prediction

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

## Project Workflow

1. Load email dataset
2. Preprocess email text
3. Convert text into numerical features using TF-IDF
4. Split data into training and testing sets
5. Train the model using Multinomial Naive Bayes
6. Evaluate model performance
7. Predict whether an email is Phishing or Safe

## Output

* Accuracy: 100%
* Confusion Matrix
* Real-time email classification

## Sample Prediction

Input:
Congratulations! You won a free iPhone.

Output:
Phishing

Input:
Meeting scheduled for tomorrow.

Output:
Safe

## Conclusion

This project successfully detects phishing emails using machine learning techniques and demonstrates the application of text classification for cybersecurity and email protection.

## Author

Thilak
