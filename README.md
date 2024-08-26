Book Recommendation System - Exploratory Data Analysis (EDA) and Recommendation Pipeline

This repository contains code for a book recommendation system, including data preprocessing, profile creation, similarity calculation, and recommendation generation.

Features

1. Data Loading and Cleaning
Datasets: Load bookData.csv, UserData.csv, UserHistoricalView.csv, and TestUserAnswers.csv.
Data Cleaning: Remove 'X' from ISBNs, handle missing values, and remove duplicates.
2. User Profile Creation
Boolean Encoding: Convert categorical features (book titles, authors, publishers, etc.) into boolean columns.
Profile Creation: Combine user historical data with book data to create user profiles based on their reading history.
3. Similarity Calculation and Recommendations
Cosine Similarity: Calculate similarity between users and books based on boolean profiles.
TF-IDF and Euclidean Similarity: Compute TF-IDF for books and users, then generate recommendations using Euclidean similarity.
Top Recommendations: Generate top-10 book recommendations for users based on similarity scores.
4. Evaluation
Metrics: Evaluate the recommendations using Precision, Recall, and F-measure.
Files


Usage

Run the code: Execute the provided code to generate user profiles, calculate similarity matrices, generate recommendations, and evaluate the system.
Modify datasets: Update the paths to your datasets as necessary.
Evaluate: Check the precision, recall, and F-measure to assess the quality of recommendations.
Requirements

Python 3.x
Pandas
NumPy
