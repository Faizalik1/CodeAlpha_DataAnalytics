# 🎬 Netflix Movies & TV Shows — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)

**Internship:** CodeAlpha — Data Analytics (Task 2 & 3)
**Author:** Faiz Ali

---

## 📋 Project Overview

A complete exploratory data analysis (EDA) of the Netflix Movies and TV Shows dataset, uncovering content trends, regional production patterns, genre popularity, and Netflix's content strategy over time.

---

## 🎯 Objective

To analyze Netflix's content library and answer key business questions:
- Does Netflix focus more on Movies or TV Shows?
- Which countries produce the most Netflix content?
- What genres and ratings dominate the platform?
- How has Netflix's content library grown over time?
- When does Netflix add the most new content?

---

## 📊 Dataset

**Source:** Netflix Movies and TV Shows dataset (netflix_titles.csv)

| Column | Description |
|--------|-------------|
| type | Movie or TV Show |
| title | Content title |
| director | Director name |
| cast | Cast members |
| country | Country of production |
| date_added | Date added to Netflix |
| release_year | Original release year |
| rating | Content rating (TV-MA, PG, etc.) |
| duration | Length (minutes or seasons) |
| listed_in | Genre categories |

---

## 🔬 Analysis Process

```
1️⃣  Import Libraries          → Pandas, Matplotlib, Seaborn
2️⃣  Load Dataset              → Initial inspection
3️⃣  Understand the Data       → Data types, statistics, missing values
4️⃣  Data Cleaning             → Handle nulls, duplicates, date parsing
5️⃣  Analysis & Visualization  → 8 detailed visual analyses
6️⃣  Summary of Findings       → Key business insights
```

---

## 🧹 Data Cleaning Steps

- Filled missing **director**, **cast**, **country**, **rating**, and **duration** values
- Dropped rows with missing **date_added** (minimal data loss)
- Converted **date_added** to proper datetime format
- Extracted **year_added**, **month_added**, and **month_name** as new features
- Removed duplicate records
- Reset DataFrame index after cleaning

---

## 📈 Visualizations & Insights

### 1. Movies vs TV Shows Distribution
Pie chart and bar chart comparing total Movies vs TV Shows on the platform.

### 2. Content Added Per Year
Line chart tracking Netflix's content growth from launch through recent years, split by type.

### 3. Top 10 Countries Producing Content
Bar chart ranking countries by number of titles produced.

### 4. Top 10 Genres
Most common genres across the platform (genres split from multi-category field).

### 5. Content Ratings Distribution
Breakdown of content by audience rating (TV-MA, TV-14, PG, etc.)

### 6. Monthly Content Addition Pattern
Identifies which month Netflix typically adds the most new content.

### 7. Movie Release Year Distribution
Histogram showing the age distribution of movies available on Netflix.

### 8. Year × Month Heatmap
Visual heatmap showing exactly when Netflix added content most aggressively.

---

## 🔑 Key Findings

- **Movies dominate** Netflix's content library compared to TV Shows
- **The United States** is the largest contributor of Netflix content globally
- Netflix experienced **rapid content growth between 2015–2019**
- **International Movies and Dramas** are the most popular genres
- Netflix strategically adds the most content during **specific months** of the year
- The majority of content carries a **TV-MA or TV-14 rating**, indicating adult-oriented programming

---

## 🛠️ Technologies Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 📁 Project Structure

```
netflix-eda-analysis/
│
├── Netflix_EDA.ipynb              ← Main notebook
├── netflix_titles.csv             ← Dataset
├── 01_movies_vs_tvshows.png
├── 02_content_per_year.png
├── 03_top_countries.png
├── 04_top_genres.png
├── 05_ratings.png
├── 06_monthly_additions.png
├── 07_movie_release_years.png
├── 08_heatmap.png
└── README.md
```

---

## 🚀 How to Run

```bash
# 1. Clone repository
git clone https://github.com/Faizalik1/netflix-eda-analysis.git
cd netflix-eda-analysis

# 2. Install requirements
pip install pandas numpy matplotlib seaborn jupyter

# 3. Run notebook
jupyter notebook Netflix_EDA.ipynb
```

---

## 🎓 Skills Demonstrated

- Data Cleaning & Preprocessing
- Handling Missing Values
- DateTime Feature Engineering
- Exploratory Data Analysis (EDA)
- Multi-category Field Processing (genre splitting)
- Data Visualization (Matplotlib & Seaborn)
- Heatmap & Time-Series Analysis
- Business Insight Generation

---

## 🔗 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Faiz_Ali-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/faiz-ali-03365b217)
[![Email](https://img.shields.io/badge/Email-faizalics1@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:faizalics1@gmail.com)

---

<p align="center">
  <i>Project by Faiz Ali | CodeAlpha Data Analytics Internship</i>
</p>
