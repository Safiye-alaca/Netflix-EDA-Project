# 🎬 Netflix & Spotify Exploratory Data Analysis (EDA)

This project focuses on **Data Cleaning** and **Exploratory Data Analysis (EDA)** using Netflix and Spotify datasets. The core objective is to master transforming raw, messy text data into actionable insights using **Regex (Regular Expressions)** and **Pandas String Methods**.

---

## 📌 Project Overview
In data science, cleaning often takes 80% of the time. This project demonstrates practical data wrangling on real-world datasets (Netflix/Spotify).

### 🎯 Key Objectives:
* Use `str.split` and `explode` to handle cells with multiple values (e.g., Cast or Genre).
* Apply `str.extract` with **Regex** to pull numerical data (e.g., number of seasons) from text.
* Optimize memory usage by converting object types to `category`.
* Discover content trends through advanced data visualization.

---

## 🛠️ Tech Stack
* **Python 3.x**
* **Pandas:** Data manipulation and string methods.
* **NumPy:** Numerical computations.
* **Matplotlib & Seaborn:** Statistical data visualization.
* **Regex (re):** Text mining and pattern matching.

---

## 🚀 Workflow

### 1. Data Cleaning
* **Missing Value Analysis:** Identifying and strategically filling `NaN` values.
* **Text Parsing:** Splitting comma-separated values in the "Cast" and "Listed_in" columns.
* **Regex Magic:** Extracting digits (e.g., pulling "8" from "8 Seasons") using the `(\d+)` pattern.

### 2. Analysis & Visualization (EDA)
* **Genre Analysis:** Frequency analysis of the most produced content types.
* **Director Impact:** Identifying which directors dominate specific genres.
* **Spotify Correlation:** Visualizing the relationship between "Danceability" and "Energy" using Heatmaps.

├── notebooks/          # Step-by-step Jupyter Notebooks
├── reports/            # Generated plots and insights
└── README.md           # Project documentation
