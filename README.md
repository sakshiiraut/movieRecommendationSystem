🎬 Movie Recommendation System
This project is a content-based movie recommendation system built using Python, Streamlit, and machine learning. It recommends similar movies based on the user's selected movie by analyzing movie content and using cosine similarity.

🚀 Features
- Recommends top 5 similar movies
- Displays movie posters using TMDb API
- Clean and interactive UI using Streamlit
- Fast response with preprocessed similarity matrix

🛠️ Tech Stack
- **Python**
- **Streamlit**
- **pandas**
- **scikit-learn**
- **Pickle**
- **TMDb API**

📂 Project Structure
movieRecommendationSystem/
├── app.py # Streamlit application
├── movie.pkl # Preprocessed movie data
├── similarity.pkl # Cosine similarity matrix
├── requirements.txt # Dependencies
└── README.md 

🧠 How It Works
movie.pkl contains cleaned and structured metadata of movies.
similarity.pkl stores a precomputed cosine similarity matrix based on movie features like genres, keywords, etc.
When a movie is selected, the app fetches the top 5 most similar movies using cosine similarity and shows them along with their posters fetched via TMDb API.
