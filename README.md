This project is a hybrid movie recommender system built with Python as part of my CodSoft Artificial Intelligence Internship.
It combines Content-Based Filtering (TF-IDF + Cosine Similarity) and Collaborative Filtering (User-Based Similarity) to recommend movies.

🔹 Features

Content-Based Filtering

Uses TF-IDF Vectorization on movie descriptions

Finds movies similar to a given title or keyword query

Collaborative Filtering

Builds a user-movie rating matrix

Predicts ratings using cosine similarity between users

Hybrid Approach

Combines both methods with adjustable weighting (alpha_content)

Returns ranked movie recommendations

🔹 Tech Stack

Python 3

pandas, numpy for data handling

scikit-learn for TF-IDF and similarity

Custom hybrid recommender function

🔹 How to Run

Clone the repository

git clone https://github.com/ANUJK17/codsoft_movierecommandation.git


Navigate to the project folder

cd codsoft_movierecommandation


Run the script

python codsoft_movie_recommendation.py
