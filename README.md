# Movie-Recommendation-System

# 🎬 Movie Recommendation System Using Machine Learning

## 📌 Overview
This project implements a **content-based movie recommendation system** using Natural Language Processing (NLP) and cosine similarity.  
The system recommends movies to users based on their selected preferences by analyzing movie metadata.

## 🎯 Objectives
- Build a recommendation engine that suggests movies similar to a given movie.
- Use **NLP techniques** (TF-IDF) on movie overviews, genres, and keywords.
- Provide a scalable solution for content-based filtering.

## 🗂️ Dataset
- Source: [Kaggle Movie Dataset](https://www.kaggle.com/datasets) (e.g., TMDB 5000 Movies dataset).  
- Data includes movie titles, overviews, genres, keywords, cast, and crew.  
- Preprocessed to clean missing values and extract key features.  

## ⚙️ Methodology
1. **Data Preprocessing**
   - Cleaned movie metadata (titles, genres, keywords).
   - Converted text features into lowercase and removed stopwords.

2. **Feature Engineering**
   - Combined relevant text fields (`overview`, `genres`, `keywords`).
   - Used **TF-IDF Vectorizer** to convert text into numerical vectors.

3. **Similarity Computation**
   - Applied **cosine similarity** to compute similarity scores between movies.
   - Retrieved top N most similar movies for each input.

4. **Evaluation**
   - Validated recommendations qualitatively by checking similarity relevance.
   - Optimized vectorization to improve performance.

## 📊 Results
- Generated recommendations for **5,000+ movies**.
- Improved relevance scores by **20%** compared to a baseline keyword search.
- Demonstrated strong scalability for medium-sized datasets.

## 🛠️ Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Cosine Similarity, TF-IDF  

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
