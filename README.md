# 🛡️ Women Safety Support Chatbot

An AI-powered women safety support chatbot built using **Python, Natural Language Processing (NLP), Machine Learning, and Flask**.

The chatbot analyzes a user's message and classifies it into different safety-related categories. Based on the detected category, it provides an appropriate safety response and risk level.

---

## 📌 Project Overview

The Women Safety Support Chatbot is designed to provide quick initial support when a user describes a potentially unsafe situation.

The system uses a Machine Learning text classification model to understand the user's message and classify it into one of seven categories:

- Stalking
- Online Threat
- Domestic Violence
- Harassment
- Physical Danger
- Emergency Help
- General Support

The chatbot then generates a category-specific response containing safety guidance.

> ⚠️ This project is intended as an educational/support system and should not replace emergency services or professional assistance.

---

## ✨ Features

- 🤖 Machine Learning based text classification
- 💬 Natural Language Processing for user messages
- 🚨 Seven safety-related categories
- 🔴 Risk-level based responses
- 🌐 Flask web application
- 🇬🇧 English and Hinglish-style input support
- 📞 Emergency support information
- 📍 Location-sharing support in the web interface
- 📊 Model evaluation using accuracy, precision, recall and F1-score
- 🧪 Separate test dataset for evaluation

---

## 🧠 Machine Learning Model

The project uses:

- **TF-IDF (Term Frequency-Inverse Document Frequency)** for converting text into numerical features
- **N-gram features** with unigram and bigram support
- **Logistic Regression** for text classification

### Machine Learning Pipeline

```text
User Message
     ↓
Text Input
     ↓
TF-IDF Vectorization
     ↓
Logistic Regression
     ↓
Category Prediction
     ↓
Risk Level
     ↓
Safety Response