# Neural_Networks_Project

Type of project : Spam Classification 

Team Members :

Adonia Sequeira        : GitHub - https://github.com/AdoniaSequeira

Ganesh Kumar Rajasekar : GitHub - https://github.com/GaneshKumarRajasekar
              
Dataset Link : https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset/data

# 📧 Neural Network-Based Spam Detection using LLMs

Email and messaging platforms are integral to modern communication—but so is the persistent issue of spam. This project tackles that challenge using cutting-edge **Natural Language Processing (NLP)** techniques, particularly **Large Language Models (LLMs)**, to build a reliable and intelligent spam classification system.

## 🧠 Project Overview

This repository demonstrates a robust pipeline for email spam detection by comparing traditional and modern NLP methodologies. It leverages:

- **Universal Sentence Encoder (USE)** for semantic embeddings
- **BERT** for contextual language representation
- **Logistic Regression & Deep Neural Networks** as classifiers

The goal is twofold:

1. Build an effective spam detection system that enhances user experience
2. Explore how LLMs add value to real-world NLP problems

## 🚀 Features

- 📜 Text cleaning and preprocessing
- 🔤 Embedding generation via USE and BERT
- 🧮 Model training with Logistic Regression and Neural Networks
- ⚖️ Handling class imbalance with weights
- 📊 Evaluation via Accuracy, Precision, Recall, F1-score
- 🧪 Real-time text classification
- 📈 Visual comparisons and performance metrics

## 📄 Project Description

> Email and messaging applications have become vital instruments in our lives, but the problem of spam messages remains. These unsolicited messages can clog inboxes and impede communication. This project seeks to develop an advanced spam detection system based on the most recent natural language processing (NLP) techniques, with a focus on Large Language Models (LLMs).

> Instead of depending entirely on traditional methods, we explore how LLMs can enhance spam detection. We use tools such as the Universal Sentence Encoder (USE) to generate meaningful text embeddings, and examine BERT-based models for classification. Prompts and intuitive evaluation via LLMs are also considered to show their practical value.

> The study compares algorithmic performance using **Precision**, **Recall**, and **F1-score**, laying the groundwork for future advancements in spam filtering systems.

## 📊 Model Performance (Example Results)

| Model Type           | Embedding | Accuracy |
|----------------------|-----------|----------|
| Logistic Regression  | USE       | 0.96     |
| Logistic Regression  | BERT      | 0.97     |
| Neural Network       | USE       | 0.98     |
| Neural Network       | BERT      | 0.98     |

## 🧰 Tech Stack

- Python 3.x
- TensorFlow / Keras
- PyTorch
- Scikit-learn
- TensorFlow Hub
- Transformers (Hugging Face)
- Matplotlib, Seaborn
