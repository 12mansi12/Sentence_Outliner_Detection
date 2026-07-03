# 🧠 Sentence Outlier Detection using Sentence Transformers

> Detecting the most semantically different sentence using AI-powered sentence embeddings and cosine similarity.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NLP](https://img.shields.io/badge/NLP-SentenceTransformers-green)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?logo=pytorch)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange?logo=googlecolab)

---

## 📖 About the Project

This project uses **Sentence Transformers** to convert sentences into high-dimensional embeddings and measures their semantic similarity using **Cosine Similarity**.

Instead of comparing words directly, the model understands the **meaning** of each sentence and identifies the one that is least similar to all others (the **outlier**).

---

## ✨ Features

✅ Sentence Embedding Generation

✅ Cosine Similarity Matrix

✅ Semantic Analysis

✅ Outlier Sentence Detection

✅ Fast & Lightweight

---

## 🛠️ Tech Stack

- 🐍 Python
- 🤖 Sentence Transformers
- 🔥 PyTorch
- 📓 Google Colab

---

## ⚙️ Workflow

```text
Input Sentences
       │
       ▼
Sentence Transformer Model
       │
       ▼
Sentence Embeddings
       │
       ▼
Cosine Similarity Matrix
       │
       ▼
Average Similarity Score
       │
       ▼
Detect Outlier Sentence
```

---

## 📌 Example

### Input

```
I love playing football.
I enjoy playing soccer.
She is reading a novel.
She is reading a book.
The weather is sunny today.
```

### Output

```
Outlier Sentence:
"The weather is sunny today."

Average Similarity: 0.2940
```

---

## 💡 Real-World Applications

🔹 Semantic Search

🔹 Text Clustering

🔹 Duplicate Detection

🔹 Data Cleaning

🔹 NLP Research

🔹 Intelligent Chatbots

---

## 📂 Project Structure

```
Sentence-Outlier-Detection/
│
├── Sentence_Outlier_Detection.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Find the most similar sentence pair
- Support larger datasets
- Interactive Streamlit Web App
- Visualize similarity using heatmaps

---

## 👩‍💻 Author

**Mansi Tyagi**

BCA Student | AI & ML Enthusiast | Aspiring Data Analyst

⭐ If you like this project, don't forget to Star the repository!
