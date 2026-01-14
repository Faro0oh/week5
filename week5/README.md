# 🎬 Movie Recommendation System

This project is an adaptation of a playlist-based recommendation system to work with a real-world **movie dataset** from Kaggle (MovieLens).

---

## 🔧 What Was Changed

The original system was designed for song playlists. We modified it to work with movie data instead.

### Main Changes

- Replaced the song playlist dataset with the **MovieLens (latest-small)** dataset from Kaggle.
- Switched from `song_id` to `movieId`, and from `songs_df` to `movies`.
- Converted user ratings into **watchlists** (lists of movies watched by each user).
- Trained a Word2Vec model on movie watchlists instead of song playlists.
- Updated all recommendation functions to use movie titles and movie IDs.

---

## ⚙️ What Was Implemented

### 1. Data Loading
- Loaded `ratings.csv` and `movies.csv` from the MovieLens dataset.
- Merged ratings with movie metadata.

### 2. Data Processing
- Grouped movies by user to form watchlists.
- Removed users with only one movie to improve training quality.

### 3. Model Training
- Trained a Word2Vec model to learn movie embeddings based on co-occurrence patterns.

### 4. Recommendation Function
- Implemented `print_recommendations(movie_id)` to retrieve similar movies using learned embeddings.

---

## ✅ Result

The system now:
- Works with real movie data.
- Recommends similar movies given a movie ID.
- Is suitable for experimentation, learning, and extension (e.g., filtering, hybrid models).

---

## 📊 Dataset

Dataset used: **MovieLens Latest Small**  
Source: https://www.kaggle.com/datasets/grouplens/movielens-latest-small
