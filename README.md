

# 📽️ Netflix Movies EDA Project

## 📌 Project Overview

This project explores Netflix movies, specifically analyzing films released in the **1990s**. Using **exploratory data analysis (EDA)** techniques, we uncover trends, patterns, and insights about movies on the platform.

## 📂 Dataset

The analysis is based on the `netflix_data.csv` file, which contains information about Netflix movies, including:

- **Movie Title**
- **Director & Cast**
- **Release Year**
- **Genre**
- **Duration**
- **IMDB Ratings**

## 🔧 Installation & Setup

To run this notebook on your local machine:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-movies-eda.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

## 🛠️ Data Preprocessing

- **Handling missing values**: Movies with missing essential details (e.g., director, rating) were handled using imputation or removed when necessary.
- **Feature engineering**: Extracted relevant features like `release year` to focus on movies from the 1990s.

## 📊 Exploratory Data Analysis (EDA)

- **Trend Analysis**:
  - Number of movies released each year in the 1990s
  - Most common genres
  - Popular directors and actors
- **Visualizations**:
  - **Heatmap**: Showcasing correlations between features like `duration` and `ratings`
  - **Bar charts**: Displaying top-rated movies and most frequent genres
  - **Scatter plots**: Investigating relationships between movie duration and ratings

## 📈 Key Findings

🔹 The **1990s** saw a rise in certain genres, particularly *drama* and *action* movies.\
🔹 **Movie duration** varied significantly across different genres.\
🔹 Certain directors had multiple successful films during this decade.

## 🚀 Future Work

- Expanding the analysis to include Netflix series.
- Predicting movie success using machine learning models.

## 📜 License

This project is open-source and available under the **MIT License**.

---
