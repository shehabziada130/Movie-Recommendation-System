# Movie Recommendation System

## Overview

This repository implements a content-based movie recommendation system using Python. The recommendation system analyzes movie metadata such as genres, keywords, cast, and crew to suggest movies based on their content similarity.

## Dependencies

Ensure you have the required libraries installed:
Sckit-learn 
NumPy
Pandas

## Usage
### Dataset:

Download the TMDB 5000 Movie Dataset and place the CSV files (tmdb_5000_movies.csv and tmdb_5000_credits.csv) in the data directory.

## Implementation Details
The recommendation system uses a content-based filtering approach, leveraging movie metadata and cosine similarity calculations. The recommend function provides a list of recommended movies for a given input movie.

### Files
recommend_movies.py: Main script with the recommendation system implementation.
data/tmdb_5000_movies.csv: Movie dataset with information about movies.
data/tmdb_5000_credits.csv: Credits dataset with information about movie credits.
movie_list.pkl: Pickle file containing preprocessed movie data.
similarity.pkl: Pickle file containing the cosine similarity matrix.
## Acknowledgments
The dataset is sourced from TMDB 5000 Movie Dataset.
The recommendation system is inspired by content-based filtering techniques.
