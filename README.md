# 🎬 Netflix Content Insights – Python Project

This project explores Netflix’s publicly available dataset using Python, answering 12 real-world business questions around content distribution, type, rating, and production insights.

## 📌 Project Overview

The goal of this project is to analyze the composition and characteristics of Netflix’s content library — identifying trends across categories, release years, countries, ratings, and creators.

Using exploratory data analysis (EDA) techniques, we answer targeted questions that a content analyst or media strategist might ask in a real-world scenario.


## 📂 Dataset Information

Source: Kaggle – https://www.kaggle.com/datasets/shivamb/netflix-shows

Total Rows: ~8,800+

Columns: title, type, director, cast, country, release_year, rating, duration, etc.


## ❓ Business Questions Answered

1. Find show ID and director for 'House of Cards'
2. Which year had the most content releases? (Bar chart)
3. How many Movies vs TV Shows are there? (Bar chart)
4. List all Movies released in 2020
5. List all TV Shows released only in India
6. Top 10 directors with the most content on Netflix
7. Find records where:
Category = Movie and Genre = Comedy
OR Country = United Kingdom
8. How many shows include ‘Tom Cruise’ in the cast?
9. What are the different content ratings defined by Netflix?
10. Which country has the highest number of TV Shows?
11. How to sort dataset by release year?
12. Find all content where:
Movie & Genre = Drama
OR TV Show & Genre = Kids TV


## 📈 Key Insights

📺 TV Shows and Movies are both heavily represented, with a surge after 2015.

🌍 The United States leads in production count, followed by India and the UK.

🎥 Tom Cruise appears in a small number of titles — a fun filterable insight.

📅 2019 was the year with the highest volume of new content.

🎭 Most popular genres include Drama, Comedy, and Documentary.

🔞 TV-MA and TV-14 dominate ratings, indicating a young adult to adult focus.


## 🧰 Tools Used

Python 3

Pandas

Seaborn & Matplotlib

Jupyter Notebook


## 📸 Sample Visuals

content_added_by_year
![image alt](https://github.com/GauravLayak/Netflix-Analysis-using-Python/blob/423cdfb2a8f7f8331db382e214f5eab5482ad3cd/Content%20by%20Years.png)

country_vs_tvshows
![image alt](https://github.com/GauravLayak/Netflix-Analysis-using-Python/blob/423cdfb2a8f7f8331db382e214f5eab5482ad3cd/Content%20by%20Movies%20%26%20TVshows.png)



## 🚀 What I Learned

How to clean, explore, and filter structured data with Pandas

Techniques to answer real business questions from raw datasets

Categorical filtering, null value treatment, and duplicates handling

Basic plotting to validate trends


## 🗂️ Project Structure

Netflix-Analysis/
│
├── Netflix Analysis.ipynb         # Full notebook with 12 Q&A sections
├── Netflix+Dataset.csv            # Raw data file
├── assets/                        # (Optional) Chart screenshots
└── README.md                      # This file
