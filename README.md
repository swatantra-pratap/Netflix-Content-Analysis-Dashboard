# Netflix Content Analysis & Visualization Dashboard

## 📊 Project Overview

This project presents an interactive Tableau dashboard built to analyze Netflix's content catalog across movies and TV shows.

The dashboard provides insights into content distribution by country, ratings, genres, and release year, helping identify patterns and trends within the Netflix catalog.

---

## 🎯 Project Objective

The objective of this project was to transform Netflix catalog data into an interactive and easy-to-understand visual analytics dashboard.

The analysis focuses on:

- Movie vs TV Show distribution
- Content distribution by country
- Rating categories
- Top genres
- Content trends over time
- Individual title-level information

---

## 🗂️ Dataset

The dataset contains **6,234 Netflix titles** and includes the following fields:

- `show_id` — Unique identifier for each title
- `type` — Movie or TV Show
- `title` — Title name
- `director` — Director of the title
- `cast` — Cast members
- `country` — Country associated with the title
- `date_added` — Date the title was added to Netflix
- `release_year` — Original release year
- `rating` — Content rating
- `duration` — Movie duration or TV show seasons
- `listed_in` — Genre/category information
- `description` — Title description

---

## 📈 Dashboard Analysis

### 1. Movies & TV Shows by Country

A geographic visualization showing the distribution of Netflix titles across different countries.

### 2. Ratings Analysis

A bar chart showing the distribution of titles across Netflix content-rating categories.

### 3. Movies & TV Shows Distribution

A comparison of the overall number and percentage of Movies and TV Shows in the dataset.

### 4. Top 10 Genres

A ranking of the most frequently occurring genres/categories in the Netflix catalog.

### 5. Movies & TV Shows by Year

A time-series visualization showing how Netflix content has changed across release years.

### 6. Title Details

The dashboard also provides detailed information for selected titles, including type, rating, duration, release year, date added, genre, and description.

---

## 🔍 Key Insights

- Movies represent the larger share of the Netflix catalog compared with TV Shows.
- TV-MA is the most frequently occurring rating category in the dataset.
- Documentaries and Stand-Up Comedy are among the leading categories in the Top 10 genre analysis.
- Netflix content shows significant growth in the later years of the dataset.
- The geographic analysis highlights differences in Netflix content availability across countries.

---

## 🛠️ Tools & Technologies

- Tableau
- Data Visualization
- Exploratory Data Analysis (EDA)
- Dashboard Development
- Geographic Analysis
- Trend Analysis
- KPI Reporting

---

## 📷 Dashboard Preview

![Netflix Dashboard](Netflix%20Dashboard.png)

---

## 📁 Project Structure

```text
Netflix-Content-Analysis-Dashboard/
│
├── Netflix Dashboard.png
├── Netflix-Content-Analysis-Dashboard.twbx
└── netflix_titles.csv
