# Phishector: Spear Phishing Detection Tool

## Overview
Phishector is a tool designed to detect spear phishing attacks by analyzing email features. It extracts various characteristics from the email's body, subject, sender details, and URLs to classify the emails as legitimate or phishing.

## Prerequisites
To execute this project, ensure the following software and libraries are installed:
- Python 2.7 or compatible version
- Required Python Libraries:
  - `colorama`
  - `beautifulsoup4`
  - `IPy`
  - `pandas`
  - `scikit-learn`
  - `keras`
  - `joblib`
  - Other dependencies like `re`, `os`, `sys`, `email`, `pprint`, etc.

## Instructions to Execute

1. **Clone the Repository**:  
   You can download the code from the GitHub repository.
   git clone https://github.com/esamashfaq/G36
   Alternatively, you can download the attached ZIP file containing all the required source code and executable files.

2. **Run the Script**:  
   After cloning the repository or extracting the ZIP file, navigate to the project folder and execute the Python script after installing the required libraries:
   python Phishector.py

3. **Enter Email Path**:  
   The script will prompt you to enter the folder path containing the email data. Make sure the path is correctly specified for proper feature extraction.

4. **Extract Features or Run Models**:  
   Once the emails are loaded, you can choose from the menu options:
   - Extract features from the emails.
   - Run machine learning or deep learning models for classification.

5. **Model Predictions**:  
   The script supports multiple ML models like:
   - Bagged Decision Tree
   - Random Forest
   - Extra Trees
   - Adaboost
   - Stochastic Gradient Boosting
   - Voting Ensemble
   - Naive Bayes
   - SVM
   Predictions will classify emails as either "Ham" or "Spam."

## Files Included
- `Phishector.py`: Main Python script for the project.
- Pre-trained models (`.pkl` files) for machine learning predictions.
- Required data files.
- Example datasets and test email folders.

## GitHub Repository
    https://github.com/esamashfaq/G36
