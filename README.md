Phishing Website Detection System

Overview:

A productiongrade phishing website detection system built using Django, Machine Learning, and MongoDB. The system analyzes URL-based features and predicts whether a website is legitimate or malicious using a trained Random Forest model achieving up to 95% accuracy.

Tech Stack:

Python 3.10+

Django REST Framework

Scikit-learn

MongoDB

HTML / CSS / JavaScript


Machine Learning Model

Algorithm: Random Forest Classifier
Accuracy: 94–97% (depending on dataset)
Training Dataset: Phishing Websites Dataset (UCI / Kaggle)

Features

Real-time URL scanning

Machine learning classification

MongoDB scan history storage

REST API architecture

Clean modular backend structure

Production-ready project structure


How to Run

1. Install Dependencies
pip install -r requirements.txt

2. Train Model
python training/train_model.py

3. Run Server
python manage.py runserver

4. Open Frontend
Open index.html in browser.

API Endpoint
POST /api/predict/



Future Improvements

Deep Learning integration

Real-time WHOIS lookup

Blacklist API integration

Browser extension integration

Deployment on AWS / Azure
