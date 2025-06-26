# 🎬 Content-Based Movie Recommender System

This project is a **content-based filtering movie recommendation system**. It suggests similar movies based on the content features like **overview**, **genres**, **cast**, and **keywords** — no user ratings required.

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (for vectorization & similarity)
- Streamlit (for interactive UI)
- TMDb API (to fetch posters)

## 🚀 Features

- Recommends similar movies to a selected one
- Uses **TF-IDF** and **cosine similarity** for content comparison
- Fetches and displays movie posters dynamically
- Fast and simple UI with Streamlit

## 🛠 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/dhanyashree-gurukar/Movie-recommender-system.git
   cd Movie-recommender-system
   ```

2. Install dependencies
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app
    ```bash
    streamlit run app.py
    ```