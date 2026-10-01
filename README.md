# NETFLIX
# Netflix Movies and TV Shows

## Project Overview

This project was completed as part of my Data Analyst Internship.
The objective of this project was to clean, analyze, visualize, and communicate insights from a Netflix Movies and TV Shows dataset using Python and Microsoft Power BI.
The project focuses on data cleaning, visualization, and storytelling through an interactive Power BI dashboard.

## Objectives

* Clean and prepare the raw Netflix dataset
* Handle missing and incorrect values
* Standardize text values and column names
* Remove duplicate records
* Perform basic data analysis
* Create meaningful visualizations using Power BI
* Build an interactive dashboard
* Present insights through data storytelling

## Tools & Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Microsoft Power BI
* Power Query
* DAX
* Git & GitHub

## Dataset

The dataset contains information about Netflix movies and TV shows.

### Main Columns

* `show_id`
* `type`
* `title`
* `director`
* `cast`
* `country`
* `date_added`
* `release_year`
* `rating`
* `duration`
* `listed_in`
* `description`

## Data Cleaning

The raw dataset was cleaned using Python and Pandas.

### Data Cleaning Steps

1. Loaded the raw CSV dataset.
2. Checked the dataset structure and data types.
3. Standardized column headers:

   * Removed leading and trailing spaces.
   * Converted column names to lowercase.
   * Replaced spaces with underscores.
4. Checked for missing values.
5. Handled missing values in text and categorical columns.
6. Identified and corrected incorrect values in the `rating` column.
7. Moved incorrect duration values such as `66 min`, `74 min`, and `84 min` from the `rating` column to the `duration` column.
8. Standardized text values and removed unnecessary spaces.
9. Corrected data types where required.
10. Checked for duplicate records and removed them.
11. Performed a final data quality check.
12. Saved the cleaned dataset as `netflix_titles_CLEANED.csv`.


## Project Files

* `netflix_titles_RAW.csv` – Original raw dataset
* `Netflix_Data_Cleaning.ipynb` – Python notebook containing the data cleaning process
* `netflix_titles_CLEANED.csv` – Cleaned dataset
