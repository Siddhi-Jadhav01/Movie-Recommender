# Movie Recommendation System

A content-based movie recommendation engine that suggests similar movies based on genres, keywords, cast, crew, and movie metadata. Built using Machine Learning, NLP techniques, and Streamlit for an interactive user experience.

---

## Live Demo

Add your deployed Streamlit link here:

```text
(https://movie-recommender-erbhvypygxhhnkvgajb5d6.streamlit.app/)
```

---

## Overview

Finding movies that match a user's interests can be challenging due to the enormous volume of available content.

This project addresses that problem by building a recommendation engine that analyzes movie metadata and suggests similar movies using content-based filtering and cosine similarity.

Users simply select a movie and instantly receive five relevant recommendations along with movie posters fetched from the TMDB API.

---

## Features

* Content-Based Movie Recommendation
* Interactive Streamlit Web Application
* Movie Poster Retrieval using TMDB API
* Real-Time Recommendations
* Fast Similarity Search
* Clean and User-Friendly Interface

---

## Tech Stack

### Machine Learning

* Python
* Pandas
* NumPy
* Scikit-Learn

### Web Application

* Streamlit

### APIs

* TMDB API

### Data Processing

* NLP-Based Feature Engineering
* Vectorization
* Cosine Similarity

---

## Dataset

The project uses the TMDB 5000 Movies Dataset containing:

* 5000+ Movies
* Genres
* Keywords
* Cast Information
* Crew Information
* Movie Overviews
* Popularity Metrics

Files Used:

```text
tmdb_5000_movies.csv
tmdb_5000_credits.csv
```

---

## How It Works

### 1. Data Collection

Movie metadata and credits are loaded from the TMDB dataset.

### 2. Data Preprocessing

Important features are extracted:

* Genres
* Keywords
* Cast
* Crew
* Overview

These features are merged into a single text representation for every movie.

### 3. Feature Engineering

Text features are processed and converted into vectors using NLP techniques.

### 4. Similarity Matrix Generation

Cosine Similarity is used to compute similarity scores between all movies.

### 5. Recommendation

When a user selects a movie:

1. The similarity scores are retrieved.
2. Movies are ranked by similarity.
3. Top 5 recommendations are returned.
4. Posters are fetched from the TMDB API.

---

## System Architecture

```text
User Selects Movie
          │
          ▼
Movie Metadata
          │
          ▼
Feature Extraction
          │
          ▼
Vectorization
          │
          ▼
Cosine Similarity Matrix
          │
          ▼
Top 5 Similar Movies
          │
          ▼
TMDB API Poster Fetching
          │
          ▼
Streamlit User Interface
```

---


---

## Sample Output

Input:

```text
Avatar
```

Recommendations:

```text
Guardians of the Galaxy
John Carter
Star Trek
Star Trek Into Darkness
The Fifth Element
```

Movie posters are displayed alongside recommendations for a richer user experience.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
```

Navigate to the project directory:

```bash
cd movie-recommendation-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Future Improvements

* Hybrid Recommendation System
* Collaborative Filtering
* Deep Learning Embeddings
* User Authentication
* Watch History Tracking
* Mood-Based Recommendations
* LLM-Powered Movie Suggestions
* Explainable Recommendations ("Why This Movie?")

---

## Key Learnings

Through this project, I gained hands-on experience with:

* Recommendation Systems
* Natural Language Processing
* Feature Engineering
* Similarity Metrics
* Streamlit Deployment
* API Integration
* End-to-End ML Project Development

---

## Author

**Siddhi Jadhav**

Computer Engineering Student
National Institute of Technology Kurukshetra

Interests:

* Machine Learning
* Data Science
* Artificial Intelligence
* Recommendation Systems

---

⭐ If you found this project useful, consider giving it a star.
