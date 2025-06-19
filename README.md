# 🧠 NLP Basics with NLTK and Keras

This project is a beginner-friendly exploration of core Natural Language Processing (NLP) tasks using Python libraries like **NLTK** and **Keras**. It walks through tokenization, stemming, lemmatization, stop word removal, vocabulary building, and sequence conversion.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Key Concepts Covered](#key-concepts-covered)
  - Sentence and Word Tokenization
  - Stemming & Lemmatization
  - Stop Words Removal
  - Vocabulary & Corpus
  - Keras Tokenizer & Text Sequences
- [Code Walkthrough](#code-walkthrough)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Output Examples](#output-examples)
- [Future Work](#future-work)

---

## 📖 Overview

This project demonstrates the foundational concepts of NLP. It includes:
- Breaking text into sentences and words
- Removing common words (stop words)
- Finding the vocabulary size
- Using Keras tokenizer to convert text to numerical format

---

## 🛠 Technologies Used

- Python 3.10
- [NLTK](https://www.nltk.org/)
- [TensorFlow Keras](https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/text/Tokenizer)

---

## 📚 Key Concepts Covered

### 📝 Sentence & Word Tokenization
- Using NLTK’s `sent_tokenize` and `word_tokenize` to split text.

### 🔄 Stemming & Lemmatization
- Using `PorterStemmer` and `WordNetLemmatizer` for word simplification.

### ❌ Stop Words Removal
- Removing commonly used English words (e.g., "is", "the") using NLTK.

### 📦 Corpus & Vocabulary
- Creating a corpus, removing special characters, and calculating vocabulary size.

### 🔢 Keras Text Sequences
- Using `Tokenizer` to:
  - Convert text to sequences
  - Handle OOV (Out-of-Vocabulary) tokens
  - Limit vocabulary size

---

## 💻 Code Walkthrough

1. **Tokenization**
   ```python
   from nltk.tokenize import word_tokenize, sent_tokenize
   ```
2. Stemming and Lemmatization
   ```python
   from nltk.stem import PorterStemmer, WordNetLemmatizer
   ```
3. Stopwords
   ```python
   from nltk.corpus import stopwords
   ```
4. Keras Tokenizer
   ```python
   from tensorflow.keras.preprocessing.text import Tokenizer
   ```

---

## ⚙️ Installation
   ```
    pip install nltk
    pip install tensorflow
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')
    nltk.download('wordnet')
    nltk.download('omw-1.4')
   ```

---

▶️ How to Run

1. Clone this repository.
2. Run the Python file (.py or notebook).
3. Observe printed outputs in your terminal or notebook.

---
## 🔍 Output Examples
- Tokenized Words: ['Hello', 'Geeks', '.', 'We', "'re", ...]
- Stop Words Removed: ['good', 'time', 'talk']
- Lemmatized Words: change, change, change
- Keras Token Sequences: [[2, 3, 4], [5, 1, 3, 6]]
- Vocabulary Size: 15 (example)
 
---

## 🚀 Future Work
- Named Entity Recognition (NER)
- POS tagging
- Text classification
- Using SpaCy for more advanced NLP

---

## 📁 License
This project is licensed under the MIT License. See the LICENSE file for details.


---

Let me know if you'd like a Jupyter Notebook version of this, or if you want to turn it into a web app or blog!
