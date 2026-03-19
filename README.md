Movie Recommender System

A content-based movie recommendation system built using Machine Learning and Streamlit. 
It recommends similar movies based on user input using cosine similarity.

Features:

Recommends movies based on similarity
Uses NLP techniques on movie metadata
Fast recommendations using cosine similarity
Interactive web interface using Streamlit

Tech Stack:

Python
Pandas
Scikit-learn
Streamlit
TMDB API

Dataset:

TMDB 5000 Movies Dataset
TMDB 5000 Credits Dataset

How It Works:

Important features are combined:
Overview
Genres
Keywords
Cast
Crew
Text data is converted into vectors using CountVectorizer
Cosine similarity is calculated between movies
Top similar movies are recommended

Run Locally
Install dependencies:
pip install -r requirements.txt
Run the application:
streamlit run app.py

API Key Setup
Create a .env file in the project directory and add:
TMDB_API_KEY=your_api_key_here

Output:
Select a movie
Click "Recommend"
Get top similar movies

Future Improvements:
Add movie posters
Add ratings and reviews
Deploy application online

Author:
Pari Bardia
B.Tech Student | AI & ML Enthusiast

License

This project is for educational purposes.
