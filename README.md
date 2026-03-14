# Phishing Email Detector using Large Language Models (LLM)

## Project Overview

Phishing attacks are one of the most common cybersecurity threats that exploit human trust to steal sensitive information such as login credentials, financial details, and personal data. Traditional phishing detection techniques such as blacklists and rule-based filters often fail to detect new or sophisticated phishing attacks.

This project aims to develop a phishing email detection system using Large Language Models (LLMs) such as BERT and DistilBERT to analyze the semantic and contextual features of emails. The system will classify emails as **Phishing** or **Legitimate** using machine learning and natural language processing techniques.

---

## Objectives

The main objectives of this project are:

- To collect and preprocess phishing and legitimate email datasets.
- To train and fine-tune a transformer-based LLM model for phishing detection.
- To develop a backend API for model inference.
- To create a simple web interface for testing email classification.
- To evaluate the model using performance metrics such as Accuracy, Precision, Recall, and F1-score.

---

## Technologies Used

### Programming Languages
- Python
- JavaScript

### Frameworks and Libraries
- Flask (Backend API)
- React (Frontend)
- HuggingFace Transformers
- PyTorch
- Scikit-learn
- Pandas
- NumPy

### Tools
- Git & GitHub
- Visual Studio Code
- MongoDB Atlas
- Google Colab (for model training)

---

## Project Structure

```text
phishing-email-detector-llm
│
├── client/                 # Frontend (React application)
│
├── server/                 # Backend API
│   ├── app.py
│   └── routes/
│
├── model/                  # Machine learning model
│   ├── train.py
│   ├── predict.py
│   └── model.pkl
│
├── dataset/                # Email datasets
│
├── docs/                    #project documentation
|
|___server/                 # server and api related files
│
├── README.md
└── .gitignore
