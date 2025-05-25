#  Phishing Detection App

A machine learning-based phishing detection system that identifies phishing emails and malicious websites. Built using Python, trained on feature-rich datasets, and deployed with a simple UI for user interaction.

## Features

- Detects phishing emails using NLP and classification models
- Identifies phishing URLs using feature-based analysis
- Machine learning models trained on balanced and preprocessed datasets
- Streamlit-based UI for easy usage
- Helps raise awareness against phishing attacks

## Project Structure

── models/ # Trained models for email & URL detection
├── data/ # Cleaned datasets
├── utils/ # Feature engineering and helper functions
├── app.py # Main Streamlit application
├── phishing_app.zip # (Optional) Archived version of the app


## Models Used

- **Email Phishing Detection**: TF-IDF + Logistic Regression (optimized for precision)
- **URL Phishing Detection**: Feature-based Random Forest Classifier

## Installation

Usage

Upload an email or enter a URL in the Streamlit UI

The app will return whether it is Phishing or Legitimate

Visual outputs show which features influenced the result
