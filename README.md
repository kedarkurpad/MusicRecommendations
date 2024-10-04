# Music Recommendation System

This repository contains a recommendation system developed to suggest the top 10 songs tailored to user preferences, improving engagement on streaming platforms.

## Project Overview

With vast catalogs and diverse user tastes, delivering accurate song recommendations is essential for engagement and user satisfaction. This project explores multiple recommendation algorithms using **The Echo Nest's Million Song Dataset** and evaluates them based on predictive accuracy and personalization.

### Key Questions Addressed
1. What songs are users likely to enjoy?
2. Which features contribute to a song's popularity?
3. How can recommendation algorithms improve user engagement?

## Data Summary

The dataset consists of:
- **Song Data**: Titles, release years, and artist information.
- **User Data**: User IDs, song IDs, and play counts.

After data cleaning and preparation, we retained 400,730 entries with 3,156 unique users, 9,998 unique songs, and 3,374 unique artists.

## Model Comparisons

1. **Popularity-Based**: Simple, interpretable, but lacks personalization.
2. **Collaborative Filtering (User-User & Item-Item)**: Effective for personalization; user-user performed better with an optimized RMSE of 1.0529.
3. **Matrix Factorization**: Best performance with an optimized RMSE of 1.019, capturing latent patterns in user preferences.
4. **Content-Based**: Recommends similar songs but lacks diversity and relies heavily on item features.

### Recommended Approach
The **Matrix Factorization model** provides the most accurate recommendations with interpretability, ideal for production deployment. Future enhancements could explore hybrid models for improved diversity.
