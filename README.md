# Movie-Recommendation-System
This project implements a comprehensive movie recommendation system using the **MovieLens 100k dataset**. The system combines **user-based collaborative filtering**, **item-based collaborative filtering**, and **content-based filtering** to recommend movies to users based on ratings, similar users, and movie genres.

## Project Overview

The main goals of this project are:

- Load and preprocess movie, user, and rating data.
- Perform **Exploratory Data Analysis (EDA)** to understand user behavior and movie trends.
- Build **recommendation models**:
  - **User-Based Collaborative Filtering**: Recommends movies liked by similar users.
  - **Item-Based Collaborative Filtering**: Suggests movies similar to the ones a user liked.
  - **Content-Based Filtering**: Uses movie genres to find similar movies.
- Evaluate models using **RMSE** and **MAE** metrics.
- Provide business insights from the analysis.

---

## Dataset

The project uses the **MovieLens 100k dataset**, which contains:

- `u.data` – User ratings of movies  
- `u.item` – Movie information (titles, release dates, genres)  
- `u.user` – User demographics (age, gender, occupation)

**Merged Dataset:**  
User ratings are combined with movie details and user demographics to create a rich dataset for analysis.

---

