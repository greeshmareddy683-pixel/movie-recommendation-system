Movie Recommendation System

Project Overview

This project builds a simple Movie Recommendation System using Machine Learning.
It recommends movies similar to the one entered by the user based on movie features like overview, genres, and keywords.

The system uses content-based filtering and calculates similarity between movies using cosine similarity.

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab / Jupyter Notebook

How It Works

1. Load the movie datasets.
2. Merge movie and credits data.
3. Select important features (overview, genres, keywords).
4. Combine them into a single tags column.
5. Convert text data into vectors using CountVectorizer.
6. Calculate similarity between movies using Cosine Similarity.
7. When a user enters a movie name, the system recommends similar movies.

Dataset

The project uses the TMDB Movie Dataset.

Download from:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Files required:

- tmdb_5000_movies.csv
- tmdb_5000_credits.csv

Due to GitHub file size limits, the dataset and generated files ("movies.pkl", "similarity.pkl") are not included.
Run the notebook to generate them.

How to Run the Project

1. Download the dataset files.
2. Open the notebook "movie_recommendation_system.ipynb".
3. Run all cells.
4. Enter a movie name when prompted.
5. The system will recommend similar movies.

Example

Input:
The Dark Knight

Output:
Batman Begins
The Dark Knight Rises
Batman Forever
Everyone Says I Love You
Brooklyn's Finest
