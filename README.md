# Women Safety Support Chatbot

An AI-powered women safety support chatbot that uses Natural Language Processing (NLP) and Machine Learning to understand safety-related messages and classify them into different categories.

## Features

- Classifies user messages into safety-related categories
- Provides a risk level for each category
- Provides safety guidance based on the detected category
- Supports English and Hinglish-style messages
- Uses a local Machine Learning model
- Provides emergency support information
- Includes a separate test dataset for model evaluation
- Web-based interface using Flask

## Safety Categories

The chatbot supports the following categories:

1. Stalking
2. Online Threat
3. Domestic Violence
4. Harassment
5. Physical Danger
6. Emergency Help
7. General Support

## Machine Learning

The chatbot uses:

- TF-IDF Vectorization
- Unigram and bigram features
- Logistic Regression classifier
- Natural Language Processing with NLTK
- Scikit-learn

The model is trained locally using a dataset of 972 training sentences.

## Dataset

### Training Dataset

Total training sentences:

**972**

The dataset contains examples belonging to seven safety categories.

The training dataset is balanced according to the category-specific sentence counts used by the project.

### Test Dataset

A separate test dataset containing **28 sentences** is used to evaluate the model on examples that are not part of the training dataset.

## Model Evaluation

### Training Evaluation

Training accuracy:

**96.09%**

### Test Evaluation

Test accuracy:

**96.43%**

The separate test dataset is important because it provides an evaluation using sentences that were not used during model training.

## Technologies Used

- Python
- Flask
- Scikit-learn
- NLTK
- HTML
- CSS
- JavaScript

## Project Structure

```text
Women_Safety_Chatbot/
│
├── app.py
├── chatbot.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── templates/
    └── index.html