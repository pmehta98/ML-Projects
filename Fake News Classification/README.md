# 📰 Fake News Classification using Deep Learning

## 📌 Project Overview
Fake news detection is a critical challenge in the modern digital landscape. This project explores **deep learning techniques** to classify news articles as **fake or real**, using **pre-trained transformer models**.

We leverage two powerful NLP libraries:
- **`sentence_transformers`** – for generating high-quality sentence embeddings.
- **HuggingFace `transformers`** – for fine-tuning deep learning models on text classification tasks.

The dataset used is from **Kaggle's Fake News Classification challenge**, and the project demonstrates the application of **pre-trained models** for transfer learning in NLP.

---

## 📊 Dataset
The dataset contains labeled news articles categorized as **real** or **fake**. The primary text features include:
- **Title**: The headline of the news article.
- **Text**: The full content of the article.
- **Label**: 1 (Fake) or 0 (Real).

**Data Preprocessing Steps:**
- **Text Cleaning:** Removing punctuation, stopwords, and special characters.
- **Tokenization:** Converting text into numerical sequences.
- **Embedding Extraction:** Using `sentence_transformers` for feature representation.
- **Train-Test Split:** Preparing data for training and validation.

---

## 🛠️ Methodology

### **1️⃣ Feature Extraction using `sentence_transformers`**
- **Converts raw text into vector embeddings** using pre-trained models like **BERT**.
- Allows for efficient comparison and classification of news articles.

### **2️⃣ Model Selection & Training**
- Experimented with multiple transformer-based models, including:
  - **BERT**
  - **DistilBERT**
  - **RoBERTa**
- Fine-tuned **HuggingFace transformers** on the dataset using a **pre-trained model checkpoint**.

### **3️⃣ Performance Evaluation**
- Used **accuracy, precision, recall, and F1-score** to measure performance.
- Compared results between **fine-tuned transformers** and **baseline machine learning models**.

---

## 📈 Results & Insights
- **Transformer-based models outperformed traditional approaches**, achieving high classification accuracy.
- **Sentence embeddings significantly improved model performance** by capturing contextual meaning.
- **Pre-trained models reduced training time** while achieving state-of-the-art performance.

---
