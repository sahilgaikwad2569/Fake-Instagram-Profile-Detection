# Fake Instagram Profile Detection Using Machine Learning

## Overview

Fake accounts on social media platforms have become a major concern due to their involvement in spam, phishing, misinformation, fake engagement, and online fraud. This project presents a Machine Learning-based solution for detecting fake Instagram profiles by analyzing profile attributes and behavioral patterns.

The system utilizes machine learning algorithms to classify Instagram accounts as genuine or fake based on various account features. Multiple models are trained and evaluated to identify the most effective approach for fake account detection.

---

## Features

- Fake Instagram Profile Detection
- Machine Learning-Based Classification
- Data Preprocessing and Cleaning
- Feature Engineering
- Dataset Balancing using SMOTE
- Random Forest Classification
- Decision Tree Classification
- Neural Network Models
- Performance Evaluation
- Accuracy, Precision, Recall, and F1-Score Analysis
- User-Friendly Web Interface

---

## Problem Statement

Social media platforms contain millions of fake accounts that are used for:

- Spamming
- Phishing Attacks
- Fake Followers Generation
- Misinformation Campaigns
- Online Fraud
- Fake Engagement Manipulation

Manual detection methods are inefficient and difficult to scale. Therefore, an automated machine learning-based system is required to identify fake accounts accurately and efficiently.

---

## Objectives

- Analyze Instagram account data to identify fake profiles.
- Compare different machine learning algorithms.
- Improve fake account detection accuracy.
- Reduce manual moderation efforts.
- Enhance social media platform security.
- Provide an automated fake profile detection solution.

---

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Django

### Database
- SQLite

### Machine Learning
- Scikit-Learn
- Pandas
- NumPy
- SMOTE

---

## Machine Learning Models

The following machine learning models were implemented and evaluated:

1. Random Forest
2. Decision Tree
3. Neural Network

Among these models, Random Forest achieved the best overall performance based on Precision, Recall, and F1-Score.

---

## Dataset

The project utilizes:

- InstaFake Dataset
- IJECE Dataset

The datasets contain various Instagram profile attributes used to distinguish between genuine and fake accounts.

Example Features:

- Number of Followers
- Number of Following
- Number of Posts
- Engagement Metrics
- Profile Completeness
- Account Activity Information

---

## System Architecture

```text
User Input
     │
     ▼
Data Collection
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Engineering
     │
     ▼
Machine Learning Model
     │
     ▼
Prediction Engine
     │
     ▼
Fake / Genuine Account Result
```

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Fake-Instagram-Profile-Detection.git
```

### Move to Project Directory

```bash
cd Fake-Instagram-Profile-Detection
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Server

```bash
python manage.py runserver
```

### Open Browser

```text
http://127.0.0.1:8000/
```

---

## Project Structure

```text
Fake-Instagram-Profile-Detection/
│
├── dataset/
├── static/
├── templates/
├── media/
├── models/
│
├── manage.py
├── train_model.py
├── predict.py
├── requirements.txt
├── db.sqlite3
│
└── README.md
```

---

## Results

The trained machine learning models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

Results demonstrated that Random Forest achieved the highest detection performance and effectively classified fake Instagram accounts.

---

## Advantages

- High Detection Accuracy
- Automated Fake Profile Detection
- Scalable for Large Datasets
- Reduced Manual Effort
- Adaptable to New Fraud Patterns
- Enhanced Social Media Security

---

## Future Scope

- Real-Time Fake Profile Detection
- Deep Learning-Based Classification
- Multi-Platform Social Media Detection
- NLP-Based Content Analysis
- Image Analysis for Profile Verification
- Integration with Social Media APIs

---

## Conclusion

This project demonstrates the effectiveness of Machine Learning techniques for detecting fake Instagram accounts. By leveraging profile attributes and behavioral patterns, the system successfully identifies fraudulent accounts and improves platform security. The implementation of Random Forest, Decision Tree, and Neural Network models provides valuable insights into automated social media fraud detection.

---



## License

This project is developed for educational and academic purposes.
