# CS5720 - Home Assignment 3: Neural Networks and NLP Tasks

**Course:** CS5720 - Neural Networks and Deep Learning  
**Semester:** Summer 2025  
**Department:** Computer Science & Cybersecurity  
**University:** University of Central Missouri  

**Student Name:** Ramya Thadikonda

---

## 📘 Assignment Overview

This repository contains implementations of various NLP and deep learning tasks from Home Assignment 3. Each task is implemented using Python with libraries such as TensorFlow, NLTK, spaCy, NumPy, and HuggingFace Transformers.

---

### ✅ Q1: RNN for Text Generation

- Implemented an LSTM-based RNN to generate text character by character.
- Dataset used: Public domain text (e.g., Shakespeare).
- Steps:
  - Text preprocessing and character encoding.
  - Model built using `tensorflow.keras.layers.LSTM`.
  - Trained to predict the next character in a sequence.
  - Text generated using temperature-based sampling.

📄 **File:** `Q1_RNN_Text_Generation.ipynb`

---

### ✅ Q2: NLP Preprocessing Pipeline

- Input Sentence:  
  `"NLP techniques are used in virtual assistants like Alexa and Siri."`

- Preprocessing steps:
  - Tokenization
  - Stopword removal
  - Stemming

📄 **File:** `Q2_NLP_Preprocessing.py`

---

### ✅ Q3: Named Entity Recognition with spaCy

- Used `spaCy` to extract named entities from the sentence:  
  `"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."`

- For each entity, printed:
  - Entity text
  - Entity label (e.g., PERSON, DATE)
  - Start and end character positions

📄 **File:** `Q3_NER_spaCy.py`

---

### ✅ Q4: Scaled Dot-Product Attention

- Implemented attention mechanism from scratch using NumPy.
- Input:
  - Query (Q), Key (K), and Value (V) matrices
- Output:
  - Attention weights
  - Final weighted output

📄 **File:** `Q4_Scaled_Dot_Product_Attention.py`

---

### ✅ Q5: Sentiment Analysis using HuggingFace Transformers

- Used pre-trained sentiment analysis pipeline from HuggingFace.
- Input Sentence:  
  `"Despite the high price, the performance of the new MacBook is outstanding."`
- Output:
  - Sentiment Label
  - Confidence Score

📄 **File:** `Q5_Sentiment_Analysis_Transformers.py`

---

## 💻 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/home-assignment-3.git
   cd home-assignment-3
