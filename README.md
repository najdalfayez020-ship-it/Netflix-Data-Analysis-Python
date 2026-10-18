# Netflix Data Analysis Using Python

## Project Overview

This project was completed as part of the **Data Analysis Using Python Internship at Auspify Technologies**.

The objective of this project is to clean, analyze, and visualize a Netflix dataset using Python and common data analysis libraries. The project focuses on content distribution, country-wise analysis, and release-year trends.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Dataset

The dataset contains **8,790 Netflix titles** with 10 attributes, including content type, title, director, country, release year, rating, duration, and genre.

## Completed Tasks

### Task 1 – Netflix Data Cleaning & Preparation

- Imported and inspected the Netflix dataset.
- Checked for missing values and duplicate records.
- Standardized Country, Rating, and Type columns.
- Replaced 287 `Not Given` country values with `Unknown`.
- Exported the cleaned dataset as `netflix_cleaned.csv`.

### Task 2 – Content Type Analysis

Analyzed the distribution of Movies and TV Shows.

**Results:**
- Movies: 6,126 (69.69%)
- TV Shows: 2,664 (30.31%)

The dataset is predominantly composed of movies.

### Task 3 – Country-Wise Netflix Content Analysis

Analyzed Netflix titles by country and identified the leading countries in the dataset.

**Top Countries:**
- United States: 3,240 titles
- India: 1,057 titles
- United Kingdom: 638 titles
- Pakistan: 421 titles
- Canada: 271 titles

Unknown country records were excluded from the country ranking.

### Task 4 – Trend Analysis by Release Year

Analyzed how the number of titles varies by release year.

**Key Results:**
- Release years range from 1925 to 2021.
- The number of titles increased significantly during the 2010s.
- 2018 recorded the highest number of titles with 1,146.
- The dataset shows a decline in title counts after the 2018 peak.
- The 2021 figure should be interpreted cautiously because the dataset may not represent a complete full-year catalog.

## Key Insights

- Movies account for approximately 70% of the titles in the dataset.
- The United States has the largest number of titles among the analyzed countries.
- India and the United Kingdom are the next largest contributors.
- Release-year representation grew strongly during the 2010s and peaked in 2018.
- Data cleaning preserved all 8,790 records while improving consistency for analysis.

## Project Files

- `Netflix_Data_Analysis_Auspify_Najd_Alfayez.ipynb` – Complete Python analysis
- `netflix_cleaned.csv` – Cleaned dataset
- `screenshots/` – Visualizations and task results

## Internship

**Organization:** Auspify Technologies  
**Program:** Data Analysis Using Python Internship  
**Intern:** Najd Alfayez

## Conclusion

This project demonstrates practical skills in data cleaning, exploratory data analysis, data visualization, and interpretation of analytical results using Python.
