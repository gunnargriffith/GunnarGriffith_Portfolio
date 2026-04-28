---
title: "Book Review Site Top 200 Web Scraper"
layout: single
permalink: /projects/book-scraper/
author_profile: false
---

# Book Review Site Top 200 Web Scraper

## Overview

This project focused on building a web scraper that collected data from a popular book review website’s Top 200 books list. The scraper gathered title information, author details, average ratings, and genre/tag metadata for each book.

After collecting the data, I performed exploratory analysis to better understand trends among highly rated books, common genres, and the distribution of ratings across the Top 200 list.

## Tools Used

- Python  
- BeautifulSoup / Requests  
- Pandas  
- Data Cleaning and Visualization Libraries  

## Data Collected

For each book, the scraper collected:

- Book title  
- Author  
- Average user rating  
- Number of ratings/reviews  
- Genres / tags  
- Ranking position  

## Key Findings

## Top Genres by Average Rating

This visualization compares genres based on their average rating among books appearing in the Top 200 list.

![Top Genres by Average Rating](docs/dq_analysis_files/cell-6-output-1.png)

Some genres appear less frequently but maintain extremely strong average ratings, suggesting niche categories with highly engaged readers.

---

## Most Common Genres

This chart highlights which genres appear most often among the Top 200 books.

![Most Common Genres](docs/dq_analysis_files/cell-7-output-1.png)

The results show that a handful of broad genres dominate the rankings, reflecting overall reader popularity and market size.

---

## Distribution of Average Ratings

This histogram shows how ratings are distributed across the Top 200 books.

![Distribution of Average Ratings](docs/dq_analysis_files/cell-9-output-1.png)

Because these books are already highly ranked, ratings cluster toward the upper end of the scale with relatively little spread.

---

## Challenges

Some challenges included:

- Parsing inconsistent HTML structures  
- Cleaning duplicated or overlapping genre tags  
- Handling missing values  
- Respecting request timing while scraping pages responsibly  

## Conclusion

This project demonstrates how web scraping can be combined with data analysis to extract meaningful insights from publicly available review data. It also provided hands-on experience with data acquisition, cleaning, and visualization workflows.

## Future Improvements

Potential next steps include:

- Expanding beyond the Top 200 books  
- Comparing genres over time  
- Sentiment analysis of reviews  
- Predicting rankings using metadata  