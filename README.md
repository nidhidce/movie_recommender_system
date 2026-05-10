# 🎬 Movie Recommendation System

A Machine Learning based Movie Recommender System that suggests movies to users based on similarity between movies using content-based filtering.

---

## Project Overview

This project recommends similar movies based on genres, keywords, cast, crew, and movie overview.  
The recommendation engine uses Natural Language Processing (NLP) and cosine similarity to find related movies.

Example:
If a user searches for **Avatar**, the system recommends movies with similar content and features.

---

## Features

- Movie recommendation based on similarity
- Content-based filtering
- NLP text preprocessing
- Cosine similarity calculation
- Fast and simple recommendation engine

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

---

## Dataset

Dataset used: TMDB 5000 Movie Dataset

Files:
- tmdb_5000_movies.csv
- tmdb_5000_credits.csv

---

## How It Works

1. Data preprocessing and cleaning
2. Feature extraction from:
   - genres
   - keywords
   - cast
   - crew
   - overview
3. Combine features into tags
4. Text vectorization using CountVectorizer
5. Similarity calculation using cosine similarity
6. Recommend top similar movies

---

## 📁 Project Structure

```bash
Movie-Recommendation-System/
│
├── movie_recommender.py
├── movies.csv
├── credits.csv
├── README.md
```


## Output Example

Input:
```python
recommend("Avatar")
```

Output:
- Guardians of the Galaxy
- John Carter
- Star Trek
- The Avengers
- Alien

---

## Machine Learning Concepts Used

- NLP
- Vectorization
- Cosine Similarity
- Recommendation Systems
- Feature Engineering

---

## Future Improvements

- Add collaborative filtering
- Deploy using Streamlit
- Add poster images using TMDB API
- Improve recommendation accuracy

---

## Author

Nidhi Kumari
