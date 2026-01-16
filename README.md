# Movie Recommendation System 

This is a content-based movie recommendation system developed as part of a data science project. It analyzes metadata such as genres, keywords, language, and cast to generate personalized movie suggestions.

## Features

- Reads and processes movie metadata from CSV and JSON files
- Allows users to filter movies based on:
  - Genre
  - Release period
  - Language
  - Keywords
  - Average rating
- Returns top 10 recommended movies using Pandas-based scoring
- Includes various data visualizations (e.g., bar plots, box plots, 3D line plots)

## Technologies Used

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook
- CSV & JSON parsing

## Dataset Files

The system uses the following files as part of its dataset:

- `movies.csv`
- `movie_cast.csv`
- `movie_genre.csv`
- `movie_keywords.csv`
- `language.json`
- `person.csv`
- And more (see full file list in repo)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/B3nny18/movie-recommendation-python.git

2 Launch Jupyter Lab:
      jupyter lab

3. Open Project2-Movies.ipynb and run all cells
   Make sure all CSV and JSON files are in the same folder as the notebook
