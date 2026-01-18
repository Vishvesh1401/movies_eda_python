# IMDb Movies – Python Exploratory Data Analysis

This project performs basic exploratory data analysis (EDA) on an IMDb movies dataset
using Python and pandas. The focus is on understanding the dataset structure,
validating data quality, and extracting simple insights.

---

## Objectives
- Load and inspect the IMDb movies dataset
- Check for missing values and duplicates
- Perform basic filtering and sorting
- Use groupby and aggregation for exploratory insights
- Understand multi-genre movie data during EDA

---

## Dataset
- IMDb Movies dataset sourced from Kaggle
- Each record represents a movie with attributes such as year, genre, rating, and votes
- The `genre` column contains multiple genres stored as comma-separated values

---

## Key EDA Steps
- Data loading and structure inspection (`head`, `info`, `describe`)
- Missing value and duplicate validation
- Basic data cleaning using `dropna`
- Sorting movies by ratings and other metrics
- Aggregation using `groupby` for high-level insights
- Genre-level exploration without normalization

---

## Notes on Genre Analysis
Movies can belong to multiple genres.  
During the exploratory phase, genres are analyzed as-is without normalization
to preserve the original data structure.

---

## Tools Used
- Python
- pandas
- Jupyter Notebook

---

## Project Scope
This project is limited to **EDA only**.  
Includes basic visualisation analysis using various python libraries.
