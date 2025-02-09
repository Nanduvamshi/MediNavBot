# MediNavBot
# Overview
This project is an AI-driven chatbot designed to assist users with healthcare-related queries. It helps users navigate information about adverse drug reactions, blood pressure monitoring, hospital and pharmacy searches, and more. The chatbot leverages deep learning and natural language processing (NLP) to understand user inputs and provide relevant responses.

 # Features
Intent-based navigation – Directs users to relevant healthcare topics.
Deep Learning-powered – Uses CNNs for text classification and intent recognition.
Natural Language Processing (NLP) – Preprocesses text using NLTK and WordNetLemmatizer.
Medical Assistance – Provides guidance on adverse drug reactions, blood pressure, hospital and pharmacy searches.
Interactive Conversations – Handles greetings, goodbyes, and user queries efficiently.
Custom Knowledge Base – Uses labels.pkl for topic categorization and structured responses.
# Technology Stack
Deep Learning: Convolutional Neural Networks (CNNs), TensorFlow, Keras
Natural Language Processing (NLP): NLTK, WordNetLemmatizer
Dataset: intents.json (contains tags, responses, contexts, patterns)
Preprocessing & Training: Tokenization, Lemmatization, Text Classification
Setup & Installation
# Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/chatbot-project.git
cd chatbot-project
Install dependencies:
bash
Copy
Edit
pip install tensorflow keras nltk
Run the chatbot:
bash
Copy
Edit
python chatbot.py
# How It Works
The chatbot processes user input using NLP preprocessing.
It classifies the intent using a CNN-based model trained on intents.json.
Based on the detected intent, it fetches a relevant response from predefined categories.
The chatbot interacts with users and provides information based on healthcare-related topics.
# Future Enhancements
Expand the dataset to include more medical topics.
Integrate with external APIs for real-time medical data.
Implement voice-based interactions for accessibility.


