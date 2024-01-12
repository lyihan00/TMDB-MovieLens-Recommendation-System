# TMDB-MovieLens-Recommendation-System

## General Information
**Data**: TMDB 5000 Movie Dataset, MovieLens 20M Dataset

**Models**: BERT & ERNIE, LightFM, Graph NN

**Tools**: Python, Google Colab

## Abstract
This project addresses the critical business challenge of enhancing user engagement on a movie streaming platform through a sophisticated movie recommendation system. Users often struggle to find content that aligns with their preferences, leading to decreased engagement and potential churn. In the highly competitive streaming industry, a highly relevant and personalised experience is crucial for platform success. 

Corresponding to this business issue, the core machine learning (ML) problem involves the development of a recommendation system that accurately predicts user preferences while ensuring diverse and personalised content discovery. This involves handling complex challenges such as sparse user-item interaction data, diverse user preferences, and the cold-start problem. Our solution incorporates sophisticated ML techniques, innovative feature engineering and optimization strategies, enhancing recommendation accuracy and efficiency.

Utilising The Movie Database (TMDb) and the MovieLens 20M dataset, we merged over 5,000 movie records with extensive user interaction data, including 20 million ratings. This integrated dataset formed the foundation for our recommendation algorithms.

## Key Achievements and Highlights
● _Integration of Advanced Models_: We successfully adapted and implemented state-of-the-art models such as BERT and ERNIE, as well as NGCF and LightGCN, demonstrating our capability to harness cutting-edge AI technologies.

● _Innovative Feature Engineering_: Our team developed unique features like Genre Affinity Scores and sentiment analysis using TextBlob and VADER libraries, enhancing the system's ability to understand and predict user preferences.

● _Efficiency Optimization_: By employing techniques like PCA and t-SNE for dimensionality reduction and leveraging CUDA for accelerated model training, we significantly improved the computational efficiency of our models.

● _Hybrid Recommendation Approach_: We integrated a content-collaborative hybrid model, LightFM, addressing the prevalent cold-start problem in recommendation systems and explored enhancing the interpretability of prediction scores.

## Dataset 1
The Movie Database (TMDb) is a comprehensive dataset with information on over 5,000 movies. It has a total of 4,803 entries and 24 features, organised into 2 separate files that were merged using inner join on the movie IDs to create _tmdb_merged_cleaned.csv_:

1. _tmdb_5000_credits.csv_: This file contains general information about each movie.
2. 
3. _tmdb_5000_movies.csv_: This file provides more detailed information about the cast, crew and
production for each movie.

## Dataset 2
The MovieLens dataset captures a comprehensive record of users’ movie preferences. To ensure data integrity, only users who had rated at least 20 movies were randomly selected for inclusion. We merged the datasets with a left join to _rating.csv_ to retain all ratings by users.

1. _tag.csv_: This table stores user-generated tags for movies. (46,654 entries, 4 features)

2. _rating.csv_: This table captures user ratings. (20,000,263 entries, 4 features)

3. _movie.csv_, _link.csv_: These tables contain basic information about the movies and their TMDb ID. (27,278 entries, 3 features)







