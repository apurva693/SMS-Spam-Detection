# 📩 SMS & Email Spam Detection System

A Machine Learning-based web application that classifies messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques.

---

## 🚀 Project Overview

This project uses **TF-IDF Vectorization** and a trained Machine Learning model to detect spam messages. It is deployed using **Streamlit**, allowing users to interactively test messages in real time.

---

## 🧠 Features

* 🔍 Detects spam messages instantly
* 🧹 Text preprocessing (lowercase, tokenization, stopword removal, stemming)
* 📊 Uses TF-IDF for feature extraction
* 🤖 Machine Learning model for classification
* 🌐 Simple and interactive UI using Streamlit

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Scikit-learn
* NLTK
* Pandas / NumPy

---

## 📂 Project Structure

```
SMS-Spam-Detection/
│── email spam classifier.py      # Streamlit app
│── sms spam detection.ipynb      # Model training notebook
│── vectorizer.pkl                # Saved TF-IDF vectorizer
│── model.pkl                     # Trained ML model
│── Book1.csv                     # Dataset
│── README.md                     # Project documentation
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/SMS-Spam-Detection.git
cd SMS-Spam-Detection
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Download NLTK data

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

### 4. Run the application

```bash
streamlit run "email spam classifier.py"
```

---

## 🧪 How It Works

1. User inputs a message
2. Text is preprocessed:

   * Lowercasing
   * Tokenization
   * Removing stopwords & punctuation
   * Stemming
3. Text is converted using **TF-IDF Vectorizer**
4. ML model predicts:

   * **Spam**
   * **Not Spam**

---

## 📊 Example

| Input Message                 | Output   |
| ----------------------------- | -------- |
| "Win a free iPhone now!!!"    | Spam     |
| "Let's meet tomorrow at 5 PM" | Not Spam |

---

## 🎯 Future Improvements

* Add Deep Learning models (LSTM, BERT)
* Improve accuracy with larger datasets
* Deploy on cloud (AWS / Render / HuggingFace)
* Add multilingual spam detection

