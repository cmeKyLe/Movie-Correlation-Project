# Movie-Correlation-Project
 Data analysis project exploring correlations in a movie dataset using Python. Focused on uncovering relationships between budget, revenue, ratings, and popularity through data cleaning, transformation, and visualization.


## 📌 Project Overview

This project explores a dataset of movies to uncover relationships between various features—such as budget, revenue, ratings, and viewer engagement—through data cleaning, transformation, and statistical correlation analysis. The goal is to identify which attributes most strongly influence a movie's financial success.

The project was conducted using **Python**, with key libraries including **pandas**, **seaborn**, **matplotlib**, and **NumPy**, and is designed for reproducibility within a Jupyter Notebook environment.

---

## 🔍 Key Objectives

- Clean and preprocess raw movie data for analysis
- Handle missing and inconsistent values across columns
- Extract and correct release year from date strings
- Convert categorical variables to numerical codes for analysis
- Generate a correlation matrix to identify relationships between features
- Visualize findings using heatmaps and regression plots

---

## 🧹 Data Cleaning Highlights

- Removed rows with missing values in critical columns (e.g., `budget`, `gross`)
- Standardized the `year` column by extracting values from full `released` dates
- Converted categorical columns (`genre`, `company`, etc.) into numerical representations using pandas' `category` codes

---

## 📊 Analytical Insights

- A **strong positive correlation** (~0.74) was found between **budget** and **gross revenue**, highlighting the predictive value of production investment.
- **Votes** (viewer engagement) also showed a notable correlation with revenue.
- Most categorical attributes had weaker correlations, though they may still play supporting roles when combined with numeric features.
- These insights lay the groundwork for future predictive modeling (e.g., regression or machine learning).

---

## 🛠 Tools & Technologies

- **Python 3.x**
- **Pandas** for data manipulation
- **Seaborn & Matplotlib** for visualizations
- **Jupyter Notebook** for iterative analysis and presentation

---

## 📁 Project Structure

- `Movie Correlation Project.ipynb`: Main Jupyter notebook with code, visuals, and narrative
- `movies.csv`: The dataset used for analysis (not included for licensing reasons)
- `README.md`: Project overview and explanation
