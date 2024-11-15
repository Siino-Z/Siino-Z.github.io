# Movie Recommendation System
**Unveiling User Preferences and Predicting Movie Ratings through the Lens of Data Science.**

## Project Overview
This project dives deep into the world of movie recommendation systems, crucial tools for navigating the vast sea of content in today's digital age. By combining data science, machine learning, and user behavior analysis, we aim to predict user preferences and offer tailored movie suggestions, enhancing user satisfaction and platform engagement.

---

## Problem Statement
- **Challenge:** To accurately predict how a user will rate a movie they haven't seen based on their past preferences.
- **Objective:** Develop a robust recommendation system that improves content discovery and user satisfaction by leveraging the enriched MovieLens dataset, augmented with metadata and user-generated tags.

---

## Data Summary
- **Datasets:** Utilized the MovieLens dataset, including user ratings, movie information, and tags, enriched with IMDb data for detailed movie metadata.
- **Preprocessing:**  Cleaned and transformed the data, including handling missing values (none found), removing duplicate entries (none found), and preparing features for modeling.

---

## Key Steps in the Project

### 1. Data Preprocessing and Feature Engineering
- Removed specific characters ('|') from movie genres to create a suitable format for content-based filtering.
- Explored and visualized the distribution of ratings, movie genres, and user tags to gain insights into the data.

### 2. Modeling Approach
- **Content-Based Filtering:**  Developed a model that recommends movies based on the similarity of their genres using cosine similarity.
- **Collaborative Filtering:** Implemented various collaborative filtering techniques, including:
    - Item-based k-Nearest Neighbors (k-NN) with cosine similarity.
    - User-based BaselineOnly algorithm.
    - Model-based matrix factorization techniques like Single Value Decomposition (SVD) and SVD++.

### 3. Model Performance
- Evaluated models using Root Mean Squared Error (RMSE).
- Visualized model performance through a bar plot comparing RMSE scores for each model.
- SVD++ showed the best performance with the lowest RMSE.

---

## Recommendations
- Explore hybrid recommendation approaches combining content-based and collaborative filtering for potentially improved performance.
- Fine-tune model parameters and explore alternative algorithms to further optimize prediction accuracy.
- Incorporate user demographics and viewing history for more personalized recommendations.

---

## Conclusion
This project provides valuable insights into user behavior and movie preferences, contributing to the development of more effective recommendation systems. The models developed demonstrate promising accuracy in predicting user ratings, enhancing user satisfaction and driving platform engagement.

---

## Acknowledgments
- Fellow Student Data Scientists at ExploreAI Academy
- ExploreAI Academy team for the support and resources
- GroupLens research group for the MovieLens dataset.
- IMDb for the movie metadata.

**Explore the Project Notebook:** [project-notebook.ipynb](project-notebook.ipynb) 
