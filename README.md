# Movie Recommender System

## Overview
A simple Movie Recommender System built with Python and Streamlit that suggests movies based on your selection, complete with movie posters fetched using the TMDb API.

## Features
- Select a movie from the dropdown.
- Get five similar movie recommendations.
- View movie titles and posters.

## Technologies
- Python
- Streamlit
- TMDb API

## Requirements
1. Install required libraries:
   ```bash
   pip install streamlit requests
   ```
2. Ensure these files are present:
   - `movie_list.pkl`: Movie dataset.
   - `similarity.pkl`: Pre-computed similarity matrix.

## How to Run
1. Replace the TMDb API key in the `fetch_poster` function.
2. Run the app:
   ```bash
   streamlit run app.py
   ```



