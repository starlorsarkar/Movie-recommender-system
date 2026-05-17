# 🎬 CineMatch — Movie Recommender System

A content-based movie recommender system built with Python that suggests 5 similar movies based on your selection. Built using machine learning techniques like cosine similarity and NLP preprocessing.

---

## 📸 Demo

> Select a movie from the dropdown → Click **Show Recommendation** → Get 5 similar movies instantly.

---

## 📌 How It Works

The system analyzes movie metadata including genres, cast, crew, keywords, and overview. It combines all of this into a single `tags` column, applies NLP preprocessing (stemming), converts text into vectors using **Bag of Words**, and then calculates **cosine similarity** between all movies.

When you select a movie, it finds the top 5 most similar movies based on their cosine similarity score.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Scikit-learn | CountVectorizer + Cosine Similarity |
| NLTK | Text stemming with PorterStemmer |
| Streamlit | Web application UI |
| Pickle | Saving and loading the model |

---
