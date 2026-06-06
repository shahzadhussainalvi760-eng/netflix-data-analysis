# 🎬 Netflix Data Analysis Project

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview
This project performs a comprehensive 
Exploratory Data Analysis (EDA) on a 
Netflix movie dataset containing 9,800+ movies.
The goal is to extract meaningful insights 
about movie trends, genres, ratings, 
and popularity on Netflix.

---

## 🎯 Key Questions Answered
- What is the most frequent genre on Netflix?
- Which movie has the highest popularity?
- Which movie has the lowest popularity?
- Which year had the most movie releases?
- How are movies distributed by vote average?

---

## 📊 Key Insights Discovered

| Insight | Finding |
|:--------|:--------|
| 🥇 Most Popular Movie | Spider-Man: No Way Home (5,084) |
| 📉 Least Popular Movie | The United States vs. Billie Holiday (13.35) |
| 🎭 Most Common Genre | Drama (3,715 movies) |
| 📅 Peak Release Year | 2021 (706 movies) |
| ⭐ Most Common Rating | Average — 15,501 movies (59.4%) |
| 💎 Excellent Movies | Only 67 movies (0.3%) |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|:-----|:--------|
| Python 3.9+ | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| OpenPyXL | Excel export |
| XlsxWriter | Excel charts |

---

## 📁 Project Structure

    netflix-data-analysis/
    │
    ├── README.md
    ├── requirements.txt
    ├── .gitignore
    │
    ├── data/
    │   └── Netflix_data.csv
    │
    ├── notebook/
    │   └── netflix_analysis.ipynb
    │
    ├── output/
    │   └── Netflix_Full_Analysis.xlsx
    │
    └── images/
        ├── genre_distribution.png
        ├── top10_popular.png
        ├── vote_distribution.png
        └── movies_per_year.png

---

## 🚀 How to Run

### Step 1: Clone the repository
    git clone https://github.com/yourusername/netflix-data-analysis.git

### Step 2: Navigate to project folder
    cd netflix-data-analysis

### Step 3: Install required libraries
    pip install -r requirements.txt

### Step 4: Open Jupyter Notebook
    jupyter notebook notebook/netflix_analysis.ipynb

---

## 📈 Sample Visualizations

### Most Frequent Genres
![Genre Distribution](images/genre_distribution.png)

### Top 10 Most Popular Movies
![Top 10 Popular](images/top10_popular.png)

### Movies Released Per Year
![Movies Per Year](images/movies_per_year.png)

### Vote Average Distribution
![Vote Distribution](images/vote_distribution.png)

---

## 🔍 Data Cleaning Steps Performed

1. ✅ Loaded raw CSV data
2. ✅ Fixed encoding errors
3. ✅ Handled missing values (0.1% of data)
4. ✅ Converted data types
5. ✅ Removed duplicate records
6. ✅ Extracted Year from Release Date
7. ✅ Split Genre lists into individual rows
8. ✅ Created Vote Category bands
9. ✅ Exported clean data to Excel

---

## 💡 Key Takeaways

> 1. Drama dominates Netflix with 3,715 movies
> 2. Superhero films dominate popularity rankings
> 3. Only 0.3% of movies achieve Excellent ratings
> 4. 2021 was Netflix's peak content year (706 movies)
> 5. Popularity gap between top and bottom is 380x

---

## 👤 Author

- **Name**: Your Name
- **GitHub**: [@yourusername](https://github.com/yourusername)
- **LinkedIn**: [Your LinkedIn](https://linkedin.com/in/yourprofile)

---

## 📜 License
This project is licensed under the
MIT License - see the LICENSE file for details.
