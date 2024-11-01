# Recommender System for a Medical Supplies Company

This project focuses on developing a recommendation system for a medical supplies company to boost incremental sales through personalized suggestions. The analysis includes data preparation, missing data handling, and two main recommendation approaches. These methods aim to enhance user engagement by promoting the company's most popular products and identifying product relationships.

![Medical Supplies](https://affordablemedmart.com/wp-content/uploads/2014/02/front-room-e1609957135987.jpg)

## Table of Contents

- [Project Overview](#project-overview)
- [Data Preparation](#data-preparation)
- [Recommendation Systems](#recommendation-systems)
- [Similarity Analysis](#similarity-analysis)
- [Libraries Used](#libraries-used)

## Project Overview

The primary goal of this project is to support a medical supplies company in increasing sales by recommending products based on their popularity and user similarity. The analysis covers the following main components:

1. **Data Preparation**: Cleaning and processing the dataset, handling missing values, and extracting key insights on product popularity.
2. **Recommendation Systems**: Building two types of recommenders:
   - **Popularity-based Recommender**: Recommends products based on sales volume and revenue.
   - **Matrix Factorization-based Recommender**: Utilizes collaborative filtering for personalized recommendations.
3. **Similarity Analysis**: Applying cosine similarity on product descriptions to identify relationships between products.

## Data Preparation

The dataset requires preprocessing, including handling missing data and identifying popular products by sales volume and revenue. The preparation phase also involves recognizing companies with the highest purchase volumes, which can help tailor the recommendations further.

## Recommendation Systems

### Popularity-based Recommender

The popularity-based model suggests products that are frequently bought or generate high revenue, ensuring that users see the most in-demand items.

### Matrix Factorization-based Recommender

Using collaborative filtering, this approach personalizes recommendations by analyzing purchase patterns and user preferences, offering a customized shopping experience.

## Similarity Analysis

Cosine similarity is applied to product descriptions, enabling the system to identify and recommend products with similar features. This approach enriches personalization, encouraging users to explore related products.

## Libraries Used

- **pandas**: For data manipulation and cleaning processes.
- **numpy**: To handle numerical operations during matrix factorization.
- **scipy**: Used in cosine similarity calculations to identify product relationships.
- **scikit-learn**: Provides tools for implementing machine learning models, including the collaborative filtering algorithm.
