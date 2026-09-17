# Product Price Tracker

## Overview

This Python project retrieves a product’s title and current price from the Michaels website. It records the information with the current date and can automatically append a new observation to a CSV file once per day.

The project:

1. *Sends a request to a Michaels product page.*
2. *Parses the HTML using Beautiful Soup.*
3. *Extracts the product title from the page heading.*
4. *Retrieves the price from the page’s Open Graph metadata.*
5. *Adds the current date.*
6. *Creates and appends observations to a CSV file.*
7. *Uses a timed loop to check the price every 24 hours.*

## Tools Used

- Python
- Beautiful Soup
- Requests
- pandas

## Repository Contents

- `product_price_tracker.ipynb`*– Web-scraping and price-tracking code
- `README.md`– Project documentation

## Notes

The daily tracking loop operates only while the notebook and Python kernel remain running. The generated CSV is not included because it contains temporary test observations.

## Acknowledgement

*This was completed as a guided project based on Alex The Analyst’s Data Analyst Bootcamp tutorial. The original Amazon scraper was adapted to track a Michaels product because Amazon’s current page structure no longer supports the tutorial’s extraction method.*

