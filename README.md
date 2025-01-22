# Web Scraping Project - README

## Overview
This project demonstrates web scraping using Python and Selenium. The script extracts information about Amazon's bestseller books and the top lifetime-grossing movies from Box Office Mojo. The data is then saved into CSV files for further analysis.

## Prerequisites
Ensure you have the following installed:
- Python (>=3.7)
- Selenium WebDriver
- Google Chrome (or any other supported browser)
- Chromedriver (compatible with your browser version)
- Pandas library

## Setup
1. Install Python packages:
   ```bash
   pip install selenium pandas
   ```
2. Download and set up Chromedriver:
   - Visit [ChromeDriver downloads](https://chromedriver.chromium.org/downloads) and download the appropriate version for your Chrome browser.
   - Place the Chromedriver executable in a directory included in your system's PATH or specify its location in the script.

## Functionality
### Amazon Bestseller Books
1. Opens Amazon's "Bestsellers in Books" page.
2. Extract book titles and prices.
3. Saves the data into `titles.csv` and `prices.csv` files.
4. Combines the extracted titles and prices into a single CSV file named `book_data.csv`.

### Box Office Mojo - Top Lifetime Grossing Movies
1. Opens the "Top Lifetime Grossing Movies" page.
2. Extract the rank, title, lifetime gross, and release year for movies.
3. Saves the data into a CSV file named `All_data.csv`.

## Files Generated
- `titles.csv`: Contains the titles of bestseller books.
- `prices.csv`: Contains the prices of bestseller books.
- `book_data.csv`: Merged file of book titles and prices.
- `All_data.csv`: Contains data of top lifetime-grossing movies.

## Script Details
### Libraries Used
- `selenium`: For web scraping.
- `pandas`: For data manipulation and saving data to CSV files.

### Notebook Workflow
1. Import required libraries.
2. Initialize the Selenium WebDriver.
3. Scrape data from the target websites using XPaths.
4. Process the extracted data and save it into CSV files.


