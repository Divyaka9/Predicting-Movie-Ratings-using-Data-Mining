# 🎬 Predicting Movie Ratings using Data Mining

This project explores how **data mining and machine learning techniques** can be applied to predict movie ratings. Using the **IMDB 5000 Movie Dataset** from Kaggle, I implemented multiple classification algorithms to determine which factors contribute most to a movie’s success and how well its rating can be predicted.

---

## 📌 Project Overview
- Analyzed the **IMDB 5000 Movie Dataset** with 28 features across 5000+ movies.
- Focused on predicting **IMDb scores** as the target variable.
- Explored data through **visualization and feature engineering**.
- Implemented and compared **Decision Tree, K-Nearest Neighbors (KNN), and Random Forest** classifiers.

---

## 🔍 Why Predicting Movie Ratings?
- Helps **directors and producers** estimate how successful an upcoming movie might be.
- Provides insights into **which genres, budgets, actors, or directors** correlate with high ratings.
- Assists **film companies** in making data-driven production and marketing decisions.

---

## 🛠️ Methodology
1. **Data Cleaning & Preprocessing**
   - Removed duplicates and irrelevant features.
   - Handled missing values using imputation.
   - Encoded categorical variables and normalized continuous variables.

2. **Exploratory Data Analysis (EDA)**
   - Visualized IMDb scores across **genres, countries, directors, content ratings, and release years**.
   - Identified patterns between **budget, gross earnings, Facebook likes**, and IMDb scores.

3. **Model Implementation**
   - **Decision Tree** – Accuracy ~70.79%
   - **K-Nearest Neighbors (KNN)** – Accuracy ~68.64%
   - **Random Forest** – Accuracy ~75.77% (best performing model)

---

## 📊 Results
- **Random Forest** outperformed other models with the highest accuracy.
- Discovered meaningful relationships:
  - Higher **budget and gross** → higher ratings.
  - Certain **genres** and **directors** consistently achieve strong IMDb scores.
  - **Social media popularity (Facebook likes)** correlates with ratings.

---

## 🚀 Applications
- **Box Office Forecasting**: Predict commercial and critical success of films.
- **Content Recommendation Systems**: Suggest promising upcoming movies to audiences.
- **Industry Insights**: Help studios allocate budgets effectively.

---

## 🛠️ Tech Stack
- **R Programming**
- Libraries: `ggplot2`, `dplyr`, `caret`, `randomForest`, `FNN`, `corrplot`, `plotly`, etc.

---

## 📎 Dataset
- Source: [IMDB 5000 Movie Dataset – Kaggle](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset)
- Size: ~1.43 MB
- Features: 28 attributes (director, actors, genres, budget, gross, ratings, etc.)
