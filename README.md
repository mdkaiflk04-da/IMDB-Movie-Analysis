# 🎬 IMDB Movie Analysis

An exploratory data analysis (EDA) and visualization project on the **IMDB Movies Dataset** using Python. The project involves data cleaning, answering analytical questions, and creating insightful visualizations using Matplotlib and Seaborn.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `IMDB-Analysis.ipynb` | Jupyter Notebook with complete analysis — cleaning, EDA & visualizations |

---

## 🗄️ Dataset

The dataset (`movies.csv`) contains the following key columns:

| Column | Description |
|--------|-------------|
| `name` | Movie title |
| `year` | Release year |
| `rating` | IMDB rating |
| `votes` | Number of votes |
| `duration` | Movie duration (in minutes) |
| `genre` | Genre(s) of the movie |
| `gross_income` | Gross box office income (in $M) |
| `certificate` | Age certification |
| `directors_name` | Director(s) of the movie |
| `stars_name` | Lead actors |

---

## 🧹 Data Cleaning

- Removed `"min"` and commas from the `duration` column and converted it to `int`
- Stripped commas from `votes` and converted to `int`
- Removed `$`, `M`, and commas from `gross_income` and converted to `float`

---

## 🔍 EDA — Business Questions Answered

- 📊 Mean and mode of movie ratings
- 🎬 How many movies were released each year?
- 💰 Top 5 highest-grossing movies
- 🎭 Top 5 most common genres
- 🎬 Which director has directed the most movies?
- ⭐ Which genre has the highest average rating?
- ⏱️ Do longer movies have better ratings? (correlation analysis)
- 💵 Does gross income correlate with rating?
- 🎫 How does certification affect gross income?
- 🎯 What is the best genre for a debut director?
- 🔍 Identifying anomalies — low rated but high earning movies

---

## 📈 Visualizations

| # | Chart | Type |
|---|-------|------|
| Q1 | Average movie rating over the years | Line Chart |
| Q2 | Number of movies released per year | Line Chart |
| Q3 | Distribution of movie ratings | Histogram (Matplotlib) |
| Q4 | Distribution of movie ratings | Histogram (Seaborn) |
| Q5 | Top 10 most frequent actors | Bar Chart |
| Q6 | Relationship between year and rating | Scatter Plot |
| Q7 | Distribution of Gross Income and Votes | Box Plot |
| Q9 | Correlation between Rating, Votes & Gross Income | Heatmap |
| Q10 | Correlation of all numeric columns | Full Heatmap |

---

## 🛠️ Libraries Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data manipulation and cleaning |
| `matplotlib` | Basic visualizations |
| `seaborn` | Statistical visualizations |

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/mdkaiflk04-da/IMDB-Movie-Analysis.git
   ```
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook IMDB-Analysis.ipynb
   ```

> **Note:** Make sure `movies.csv` is available at `/content/movies.csv` or update the path in the notebook accordingly.

---

## 👤 Author

**Md Kaif**
- GitHub: [@mdkaiflk04-da](https://github.com/mdkaiflk04-da)
