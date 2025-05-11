# Movie Rating Prediction

This project uses regression-based machine learning models to predict the rating of a movie based on key features such as genre, director, leading actors, and vote count. It explores the full data science workflow, including data analysis, feature engineering, modelling, and evaluation.

---

## Project Overview

Using a movie dataset, this project aims to build a predictive model that estimates a film’s rating based on:

- Genre  
- Director  
- Main Actors (Actor 1, Actor 2, Actor 3)  
- Number of Votes  

The goal is to understand the factors that influence movie ratings and develop a model that generalises well on unseen data.

---

## Models Used

The following regression models were trained and evaluated:

- Linear Regression  
- Ridge Regression  
- XGBoost Regressor  
- Random Forest Regressor *(Best Performer)*  

**Random Forest** achieved the best performance with an R² score of **0.7900**, MAE of **0.4210**, and RMSE of **0.6248**.

---

## 📊 Key Visualisations

- **Correlation Heatmap** – Identifies relationships between features  
- **Feature Importance** – Highlights which features most affect ratings  
- **Actual vs Predicted Plot** – Visualises model performance on test data  

---

## Results Summary

- **Top Influential Features**: Director, Actor 1, Genre, and Vote Count had the most significant impact on predicted ratings.
- **Best Model**: Random Forest Regressor outperformed all others in prediction accuracy and error reduction.
- **Model Performance**:

| Model                    | R² Score | MAE   | RMSE  |
|--------------------------|----------|--------|--------|
| Linear Regression        | 0.7537   | 0.4963 | 0.6766 |
| Ridge Regression         | 0.7537   | 0.4963 | 0.6766 |
| XGBoost Regressor        | 0.7866   | 0.4465 | 0.6298 |
| **Random Forest Regressor** | **0.7900**   | **0.4210** | **0.6248** |

---

## Files Included

- `movie_rating_model.ipynb`: Main notebook with analysis, modelling, and visualisations  
- `images/`: Plots including Actual vs Predicted  
- `dataset/`: https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies
