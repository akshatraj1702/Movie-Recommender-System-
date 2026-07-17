# 🎬 Movie Recommendation System

A simple content-based movie recommendation system built using Python and Scikit-learn. The model recommends movies based on their content by comparing genres, keywords, cast, crew, and overview using NLP techniques.

## 🚀 How it Works

- Merged movie and credits datasets.
- Extracted relevant features such as genres, keywords, cast, crew, and overview.
- Cleaned and combined these features into a single text representation.
- Converted text into vectors using **CountVectorizer**.
- Calculated **Cosine Similarity** between movie vectors.
- Recommended the most similar movies based on similarity scores.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Pickle

## 📂 Project Structure

```
├── movie_rec.ipynb
├── README.md
└── requirements.txt
```

## 📌 Features

- Content-based movie recommendations
- NLP-based text vectorization
- Cosine similarity for finding similar movies
- Fast and lightweight recommendation engine


## 📈 Future Improvements

- Deploy using Streamlit or FastAPI
- Use TF-IDF or Word2Vec embeddings
- Add poster images using the TMDB API
- Build a collaborative filtering version
- Improve recommendations with hybrid methods

---

Built as a beginner NLP project to understand text vectorization and recommendation systems.
