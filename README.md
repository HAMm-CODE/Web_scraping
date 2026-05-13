# Web Scraping Project - Top 50 Films

## Project Description
This project scrapes the top 50 most highly-ranked films from the Wayback Machine archived version of the Everybody Wiki's "100 Most Highly-Ranked Films" page. The extracted data includes the film's average rank, title, and release year.

## Overview
This web scraping application automatically collects film data from a historical web archive and stores it in multiple formats for easy access and analysis.

## Features
- **Web Scraping**: Extracts film data from the archived Everybody Wiki page
- **Data Processing**: Parses HTML tables using BeautifulSoup and processes the top 50 films
- **Multiple Output Formats**: Saves data in both CSV and SQLite database formats
- **Data Extraction**: Captures Average Rank, Film Title, and Release Year

## Technologies Used
- **Python 3.x**
- **BeautifulSoup 4**: HTML parsing and web scraping
- **Requests**: HTTP requests to fetch web pages
- **Pandas**: Data manipulation and CSV export
- **SQLite 3**: Database storage

## Output Files
- `top_50_films.csv`: CSV file containing the top 50 films with their rankings and years
- `Movies.db`: SQLite database containing a `Top_50` table with the same data

## Data Structure
The scraped data includes three columns:
- **Average Rank**: The ranking score of the film
- **Film**: The title of the movie
- **Year**: The release year of the film

## Usage
Simply run the script to scrape the data and generate both the CSV file and SQLite database:
```bash
python webscraping_movies.py
```