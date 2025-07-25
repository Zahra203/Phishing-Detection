#  Phishing Detection App

A machine learning-based phishing detection system that identifies phishing emails and malicious websites. Built using Python, trained on feature-rich datasets, and deployed with a simple UI for user interaction.

## Features

- Detects phishing emails using NLP and classification models
- Identifies phishing URLs using feature-based analysis
- Machine learning models trained on balanced and preprocessed datasets
- Streamlit-based UI for easy usage
- Helps raise awareness against phishing attacks

## Files included

- **Ling.csv**
- **Nazario.csv**
- **Nigerian.csv**
- **Spam.csv**
- **dataset_phishing.csv**
- **phishing_detection_websites.ipynb**
- **phishing_detection_(email).ipynb**

## Models Used

- **Email Phishing Detection**: TF-IDF + Logistic Regression (optimized for precision)
- **URL Phishing Detection**: Feature-based Random Forest Classifier
- **Streamlit Web App**  : Simple and interactive UI for end-users to test the models.
- **User Management**  : Includes login functionality and a `users.json` file to manage user credentials.

##  Technologies Used

- **Python**
- **Scikit-learn**
- **Joblib** (for model serialization)
- **Streamlit** (for UI)
- **JSON** (for storing user data)

## Libraries

- streamlit
- joblib
- nltk
- numpy
- bcrypt
- bs4 (BeautifulSoup)
- re (regular expressions)
- json
- os
- ipaddress
- urllib.parse


## Installation

Usage

Upload an email or enter a URL in the Streamlit UI

The app will return whether it is Phishing or Legitimate

Visual outputs show which features influenced the result
