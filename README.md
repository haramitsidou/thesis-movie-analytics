# thesis-movie-analytics
Python-based analysis of how streaming and rental release windows impact box office performance, using real-world movie data for thesis research.
# 🎬 Movie Release Timing & Box Office Performance Analysis

**Author:** Hara Mitsidou  
**Thesis Project | MSc Marketing Analytics & Data Science**  
**Tools:** Python, pandas, statsmodels, seaborn, matplotlib

---

## 📘 Overview

This project analyzes how the release timing of movies on **rental** and **streaming platforms** affects their **box office performance**. It was conducted as part of a master's thesis in Marketing Analytics & Data Science.

Key objectives:
- Merge and clean movie datasets from **IMDb**, **Rotten Tomatoes**, and **Metacritic**
- Engineer new variables (e.g. release windows, genre dummies, sequel status)
- Visualize correlations between budget, reviews, release timing, and revenue
- Build linear regression models to evaluate factors influencing box office success

---

## 🧠 Methods

- **Data Cleaning & Merging:** Combine 3 datasets using movie title and year
- **Feature Engineering:** Add dummies for genre, sequel status, and calculate critic scores
- **Visualization:** Create heatmaps and bar plots to explore relationships
- **Modeling:** Fit OLS regression models using `statsmodels`

---

## 📁 Project Structure

```
📦thesis-analysis
 ┣ 📂data
 ┃ ┣ imdb_movies.csv
 ┃ ┣ rotten_tomatoes_movies.csv
 ┃ ┣ imdb-movies-dataset.csv
 ┣ 📂outputs
 ┃ ┣ correlation_matrix.png
 ┃ ┣ regression_summary.txt
 ┣ thesis_analysis.py
 ┗ README.md
```

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/thesis-analysis.git
   cd thesis-analysis
   ```

2. Add your datasets in the `/data` folder.

3. Install required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn statsmodels
   ```

4. Run the script:
   ```bash
   python thesis_analysis.py
   ```

5. Check the `/outputs` folder for regression results and visualizations.

---

## 📊 Sample Output

![Correlation Matrix](outputs/correlation_matrix.png)

---

## 📬 Contact

For questions, feel free to connect with me on [LinkedIn](https://linkedin.com/in/hara-mitsidou-329b53184)  
or email me at mitsidou.hara@gmail.com

---

## 📄 License

This project is for academic and educational use. Attribution appreciated.

