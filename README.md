# Netflix Movie Duration Analysis

Exploratory Data Analysis (EDA) project analyzing Netflix movie durations over time using Python.

## Project Overview

This project investigates the hypothesis that the average duration of movies on Netflix has declined over the past decade.

The analysis includes:
- Loading structured CSV data into pandas
- Data cleaning and filtering
- Subsetting movie-only records
- Exploratory Data Analysis (EDA)
- Data visualization with matplotlib
- Genre-based analysis of short-duration films

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Analysis Performed

- Created DataFrame from structured data
- Filtered TV shows vs Movies
- Visualized movie duration trends over time
- Identified impact of short-form genres (Children, Documentaries, Stand-Up)
- Scatter plot analysis of duration vs release year

## Project Structure

netflix-movie-analysis/
│
├── data/
│   └── netflix_data.csv
├── notebooks/
│   └── netflix_analysis.ipynb
├── requirements.txt
└── README.md

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook