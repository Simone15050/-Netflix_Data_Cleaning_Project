# Netflix Data Cleaning and Visualization Project 🎬📊

## 📋 Overview
This project focuses on cleaning and visualizing the Netflix Movies and TV Shows dataset using Python.  
The dataset contains information about Netflix titles including their type, director, cast, country, release year, rating, and more.

The goal was to practice real-world data cleaning, handle missing values, and create simple, clear visualizations for analysis.

---

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🧹 Data Cleaning Steps
- Filled missing values in 'director', 'cast', 'country', 'rating', and 'duration' columns with `"Unknown"`.
- Dropped rows with missing 'date_added' since date information was critical for time-based analysis.
- Created a new `year_added` column to extract the year from `date_added`.

---

## 📊 Visualizations Created
1. **Movies vs TV Shows**  
   Bar plot showing the count of Movies and TV Shows on Netflix.
   
2. **Content Added Over the Years**  
   Line plot showing how Netflix's content library has grown over time.
   
3. **Top 10 Countries Producing Netflix Content**  
   Horizontal bar plot showing the countries with the most Netflix titles (including "Unknown" for missing country data).

---

## 📂 Project Structure
```
Netflix_Data_Cleaning_Project/
├── netflix_titles.csv              # Original raw dataset
├── netflix_cleaning.ipynb           # Jupyter Notebook with cleaning and visualizations
├── netflix_titles_cleaned.csv       # Cleaned dataset output
└── README.md                        # Project documentation (this file)
```

---

## 🚀 Future Improvements
- Explore more advanced visualizations (word clouds, genre analysis, etc.)
- Build a simple dashboard using libraries like Plotly or Tableau.
- Perform deeper trend analysis (e.g., top genres by year).

---

## ✨ Author
- Jordan Brown

---

