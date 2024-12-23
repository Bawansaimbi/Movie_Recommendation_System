# Movie Recommendation System

## Description
This is a content-based recommendation system that suggests movies based on their similarity to a given movie. The project uses datasets `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` for training and evaluation.

## Features
- Generates movie recommendations using cosine similarity.
- Includes preprocessed data and a trained model.
- Evaluated with Precision, Recall, and F1-Score.

## Project Structure
- `movie_recommendation_core.ipynb`: The Jupyter Notebook with all code for preprocessing, training, and evaluation.
- `similarity.pkl`: Pickle file containing the similarity matrix.
- `movies.pkl`: Pickle file containing preprocessed movie data.
- `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`: Datasets used for training and testing.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Bawansaimbi/Movie_Recommendation_System.git
   cd Movie_Recommendation_System
