# 🎫 Support Ticket Classification & Priority Prediction System

## 📌 Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to automatically analyze customer support tickets and predict their priority level.

The system processes ticket descriptions, converts text into numerical features using TF-IDF Vectorization, and applies a Multinomial Naive Bayes classifier to categorize support tickets.

---

## 🎯 Objective

To build an intelligent support ticket classification system that helps organizations:

- Automate ticket analysis
- Reduce manual effort
- Prioritize customer issues efficiently
- Improve response time

---

## 📊 Dataset

Dataset: Customer Support Tickets Dataset

The dataset contains:

- Ticket Description
- Ticket Type
- Ticket Priority
- Customer Information
- Resolution Details

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TF-IDF Vectorization
- Multinomial Naive Bayes
- Jupyter Notebook
- VS Code

---

## 🔄 Project Workflow

### 1. Data Loading
Loaded the customer support ticket dataset using Pandas.

### 2. Data Exploration
Examined dataset structure, columns, and sample records.

### 3. Text Feature Selection
Selected Ticket Description as the primary text feature.

### 4. Text Vectorization
Converted ticket descriptions into numerical features using TF-IDF Vectorizer.

### 5. Train-Test Split
Split data into training and testing sets using an 80-20 ratio.

### 6. Model Training
Trained a Multinomial Naive Bayes classifier on the vectorized ticket descriptions.

### 7. Model Evaluation
Evaluated model performance using accuracy score.

### 8. Real-Time Prediction
Tested the model with a custom support ticket description to predict ticket priority.

---

## 📈 Results

### Ticket Type Classification Accuracy

19.66%

### Ticket Priority Prediction Accuracy

24.03%

### Sample Prediction

Input:

Customer cannot access account and reports payment failure.

Predicted Priority:

Critical

---

## 📂 Project Structure

FUTURE_ML_02

├── data/

│ └── customer_support_tickets.csv

├── notebook/

│ └── support_ticket_classifier.ipynb

├── screenshots/

├── README.md

└── requirements.txt

---

## 🚀 Future Improvements

- Use advanced NLP techniques
- Implement Deep Learning models
- Apply BERT-based text classification
- Improve classification accuracy
- Build a web-based dashboard

---

## 👨‍💻 Author

**Chethana Sri**

Computer Science & Engineering Student

Madras Institute of Technology, Anna University

Interested in Machine Learning, Full-Stack Development, and Artificial Intelligence.