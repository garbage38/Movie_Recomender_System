# Movie Recommendation System Using Machine Learning

## Introduction
The **Movie Recommendation System** is a content-based recommendation engine that suggests movies similar to the one selected by the user. This system finds the top 5 most similar movies based on various attributes such as genre, cast, and other metadata. The recommendation algorithm utilizes machine learning techniques to analyze movie data and generate recommendations.

## How It Works
This is a content-based recommendation system. It compares the features of the movies in the dataset to find similarities between them. When a user selects a movie, the system computes similarity scores and returns the 5 most similar movies.

### Tools Used
- **Python**: The programming language used to develop the recommendation system.
- **scikit-learn**: Machine learning library used for implementing similarity measures.
- **Streamlit**: A Python library used to create the web application interface.
- **pickle**: converting a Python object into a byte stream to save it to a file or database, or transfer it over a network.

### Dataset
The movie metadata is sourced from the [TMDb Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download&select=tmdb_5000_movies.csv) dataset, which provides a rich collection of features for over 5000 movies.

## Web Application
A simple web application was built using the `streamlit` library in Python. The app allows users to:
1. Select a movie from a dropdown list.
2. View the top 5 recommended movies along with their posters.

   

### Files Us![Screenshot 2024-09-06 135744](https://github.com/user-attachments/assets/03130933-d434-4bd0-9d57-cdfe4c9bf3fa)
ed
The following files are required to run the project:
- **app.py**: The main Python script that runs the Streamlit web application.
- **movie_dict.pkl**: A serialized file containing the movie dictionary used for the dropdown list.
- **movie_list.pkl**: A serialized file containing the list of all movie titles and their respective IDs.
- **similarity.pkl**: A serialized file containing the precomputed similarity matrix between movies.

## How to Run the Project
1. Clone the repository or download the project files.
2. Make sure you have Python and the required dependencies installed (`streamlit`, `scikit-learn`, etc.).
3. Run the following command in your terminal to start the web application:

   ```bash
   streamlit run app.py





This script provides an overview of the project, instructions on how to run it, and mentions the tools and files involved. Let me know if you'd like any changes!

   
