# Homework 07: Scraping with BeautifulSoup

This repository contains my submissions for the web scraping assignments from the Lede Program. The exercises demonstrate web scraping techniques using `pandas`, `requests`, and `BeautifulSoup`, with the results saved in CSV format.

## File Overview

### Assignment 1: List of U.S. Presidents

* `01-presidents.ipynb`
  A Jupyter notebook that scrapes the list of U.S. presidents from Wikipedia using `pandas.read_html`.
  I used `drop` functions creatively to clean out as many "N/A" entries as possible.
* `us_presidents.csv`
  Output CSV file containing the presidents' table.

### Assignment 2: Le Monde Article Metadata

* `02-lemonde.ipynb`
  Scrapes article metadata from [lemonde.fr](https://www.lemonde.fr/), including title, subtitle, article URL, premium status, byline, article type, and image URL.
  Includes error handling and flexible CSS selectors to handle inconsistent structures.
* `lemonde_articles.csv`
  CSV file with the scraped article data.
* The bonus auto-updating feature was too difficult for me to complete.

### Assignment 3: Arizona Third-Party Driver License Locations

* `03-az-drivers.ipynb`
  Uses `requests` with custom headers and `BeautifulSoup` to scrape third-party driver license office information from the Arizona government site.
* `az_locations.csv`
  CSV containing the name, address, contact information, and website link for each office.

### Assignment 4: Tennessee Court Search for "CAR"

* `04-tn-court.ipynb`
  Scrapes the search results for "CAR" from the Tennessee Western Bankruptcy Court’s website.
  Extracts case name, category, additional details, and PDF URLs.
* `tn_court_cases.csv`
  CSV file containing the scraped case data.

## Notes

* All websites were scraped responsibly and strictly for educational purposes only.
