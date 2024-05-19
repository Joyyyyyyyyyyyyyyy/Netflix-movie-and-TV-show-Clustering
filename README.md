# Netflix-movie-and-TV-show-Clustering

## Project Overview

This project focuses on analyzing the Netflix Dataset of movies and TV series up to 2019, sourced from the third-party search engine Flixable. With over 220 million subscribers, Netflix faces the challenge of keeping viewers engaged and preventing subscriber attrition. The primary objective of this project is to leverage Natural Language Processing (NLP) techniques to categorize content into relevant clusters, thereby enhancing the user experience through a sophisticated recommendation system. This system aims to provide personalized content suggestions, leading to improved viewer satisfaction and retention rates.

## Problem Statement

In the realm of streaming platforms, crafting an efficient content recommendation system for a diverse global audience involves understanding viewer preferences across various dimensions such as genres, regions, release years, and content attributes. This project utilizes machine learning approaches, including K-Means Clustering and Hierarchical Clustering, to identify distinct content clusters based on multiple criteria. The goal is to extract actionable insights that can inform better content development strategies and to develop a robust recommendation system that delivers personalized content recommendations, thus boosting viewer engagement and improving content creation methods globally.

## Dataset Description

The Netflix Movies and TV Shows Clustering Dataset includes the following variables:

show_id: Unique identifier for each movie/show.
type: Indicates whether the entry is a movie or a TV show.
title: Name of the movie or TV show.
director: Name of the director(s) of the movie or TV show.
cast: Names of the actors and actresses featured in the movie or TV show.
country: Country or countries where the movie or TV show was produced.
date_added: Date when the movie or TV show was added to Netflix.
release_year: Year when the movie or TV show was released.
rating: TV rating or movie rating of the movie or TV show.
duration: Length of the movie or TV show in minutes or seasons.
listed_in: Categories or genres of the movie or TV show.
description: Brief synopsis or summary of the movie or TV show.
## Project Workflow

The project was completed through the following steps:

1. Data Preprocessing:
- Handling null values in the dataset.
- Managing nested columns for better presentation (director, cast, listed_in, country).
- Sorting the rating attribute into categories (adult, children's, family-friendly, and unrated).

2. Exploratory Data Analysis (EDA):
- Conducting EDA to gain insights on subscriber churn prevention.

3. Feature Engineering:
- Creating clusters using features such as director, cast, nation, genre, rating, and description.
- Tokenizing, preprocessing, and vectorizing these features using the TF-IDF vectorizer.

4. Dimensionality Reduction:
- Applying Principal Component Analysis (PCA) to reduce the dimensionality of the dataset for improved performance.

5. Clustering:
- Using K-Means Clustering and Agglomerative Hierarchical Clustering algorithms.
- Determining the appropriate number of clusters (4 for K-Means, 2 for hierarchical clustering) using various assessment techniques.

6. Recommendation System:
- Developing a content-based recommender system using a cosine similarity matrix to provide personalized recommendations to users, aimed at reducing subscription churn.

## Results and Insights

This comprehensive analysis and the subsequent recommendation system are designed to enhance customer satisfaction, leading to increased retention rates for Netflix. By categorizing content into meaningful clusters and providing tailored recommendations, Netflix can better meet the diverse preferences of its global audience, ultimately improving engagement and reducing churn.

## Conclusion

The Netflix Movie and TV Show Clustering project showcases the application of NLP and machine learning techniques to address real-world challenges in the streaming entertainment industry. The developed recommendation system not only offers personalized content suggestions but also provides valuable insights that can guide future content development strategies.
