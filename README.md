# Bookscrape-trends
A data pipeline and dashboard project that scrapes book metadata from Goodreads' **Best Books of 2025** list, cleans and transforms the results, and explores book popularity and reader-interest trends in Power BI.

## Overview
This project collects book-level data such as title, author, publication date, genres, page count, language, ratings, and reader-interest metrics. The cleaned dataset is then used for exploratory analysis and dashboarding.

The goal is to answer questions like:
- Which books are generating the most reader interest?
- How do ratings relate to popularity?
- Which genres appear most often?
- Do page length or publication timing seem related to engagement?

## Dataset
The dataset includes fields such as:
- `book_title`
- `publication_date`
- `author`
- `genres`
- `num_pages`
- `rank`
- `language`
- `curr_readers`
- `want_read`
- `avg_rating`
- `num_ratings`

## Workflow
1. Scrape book data from Goodreads using Selenium
2. Store the raw results
3. Clean and standardize fields in Python
4. Prepare the dataset for analysis
5. Build a Power BI dashboard for trend exploration

## Tech Stack
- Python
- pandas
- NumPy
- Selenium
- Jupyter Notebook
- Power BI

## Project Structure
```text
bookscrape-trends/
├── data/               # raw and/or cleaned data files
├── processing.ipynb    # scraping, cleaning, and transformation workflow
├── utils.py            # helper functions
├── sample.env          # sample environment variables
├── README.md
└── .gitignore
```

## Dashboard
<img width="1134" height="633" alt="image" src="https://github.com/user-attachments/assets/caa05760-ee45-43f2-bf09-651b59008dcc" />

<img width="1155" height="644" alt="image" src="https://github.com/user-attachments/assets/d5707d09-a17e-4d1e-9858-566b0199ecd2" />

<img width="1156" height="650" alt="image" src="https://github.com/user-attachments/assets/0c6b458a-6fb2-4d13-aad0-9c57048af80a" />
