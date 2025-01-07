# Movie Recommender System

# Types of Recommender System
1. **Content-Based Recommender System**: Suggests items based on the similarity between item features and the user's preferences or past interactions.
2. **Collaborative Filtering Recommender System**: Predicts user preferences by analyzing patterns in the behavior of similar users or items.
3. **Hybrid Recommender System**: Combines multiple recommendation techniques (e.g., content-based and collaborative filtering) to improve accuracy and overcome individual limitations.
     
# Project Flow
1. Dataset Details
2. Pre-processing
3. Model Building

# Dataset Details

## **1. Movies Dataset** (tmdb_5000_movies.csv)
Contains information about movies, including:

budget: Production budget (USD)

genres: Movie genres

id: Unique movie identifier

original_language: Movie language

release_date: Release date

revenue: Revenue (USD)

runtime: Movie runtime (minutes)

vote_average: Average user rating (1-10)

vote_count: Number of user votes

## **2. Credits Dataset** (tmdb_5000_credits.csv)
Provides credits information, including:

movie_id: Unique movie identifier (links to Movies dataset)

cast: List of actors and their roles

crew: List of crew members and their roles (e.g., director, writer)

# Pre-processing

1. Combined both the dataset
2. Keeping the important columns only

    - budget

    - homepage

    - id

    - original_language

    - original_title

    - popularity

    - production_comapny

    - production_countries

3. Performed Data preprocessing on above columns

4. Created new column called Tags which is concatination of above columns

# Text Vectorization (Bag of Words (BoW))

Text vectorization is the process of converting textual data into numerical format for machine learning models to process. In this project, text data (like genres, keywords, cast, and crew) is transformed into vectors to enable efficient computation and analysis

Bag of Words (BoW): Represents text as a matrix of word occurrences, ignoring grammar and word order.

![download](https://github.com/user-attachments/assets/6a6e4fc7-f87b-4c60-b515-98e11cbf09fd)


