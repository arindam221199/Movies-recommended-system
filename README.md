# CinePick — Content-Based Movie Recommender

**A Python-powered content-based recommender system with a Streamlit frontend for interactive movie suggestions.**

---

##  Features
- Built a content-based recommender engine using **TF-IDF vectorization** and **cosine similarity** on movie metadata such as titles, overviews, genres, cast, keywords, and directors.
- Delivered personalized recommendations by determining similarity between the feature vectors of movies.
- Wrapped the recommendation logic in a clean and responsive **Streamlit web application**, enabling real-time queries and a user-friendly interface.

---

##  Tech Stack
- **Language & Libraries:** Python, TF-IDF (from `sklearn.feature_extraction.text`), `sklearn.metrics.pairwise.cosine_similarity`
- **Frontend:** Streamlit
- **Data Processing:** Pandas, Numpy

---

##  Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/arindam221199/Movies-recommended-system
    cd Movies-recommended-system
    ```

2. Run the Streamlit app:
    ```bash
    streamlit run movies.py
    ```

3. Open your browser and navigate to:
    ```
    http://localhost:8501
    ```

---

##  Project Structure

├── movies.py # Streamlit app for the recommendation interface
├── movie-recommended-system.ipynb # Core logic: TF-IDF vectorization + cosine similarity
├── data/
│ ├── movies.csv # Movie metadata (titles, overviews, genres, cast, keywords, directors)
│ └── ... # Additional datasets if required
└── README.md # Project overview
