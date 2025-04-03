# Overview
This project is a simple movie recommendation system that suggests movies based on user preferences. The system uses content-based filtering or collaborative filtering techniques to provide personalized recommendations.

# Dataset used
https://drive.google.com/file/d/17CHjZkxMhZu6XB1Ml1b_DvfRy_YHUl3F/view?usp=sharing

# Features
- Recommends movies based on user input.
- Uses TF-IDF vectorization and cosine similarity to find similar movies.
- Handles large movie datasets efficiently.
- Provides a ranked list of recommended movies.

# Technologies used
- Python
- Pandas & NumPy (Data Processing)
- Scikit-Learn (Machine Learning)
- Difflib (String Matching)
- Jupyter Notebook (Development Environment)

# Model Implementation
- The dataset is preprocessed using Pandas.
- TF-IDF vectorization is applied to convert text data into numerical representations.
- Cosine similarity is computed between movies.
- The Difflib library is used for better string matching when users input movie titles.
- The most similar movies are recommended based on computed similarity scores.
