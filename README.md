# Flipkart Mobile Data Scraping Using Python

## Overview

This project demonstrates web scraping of mobile phone data from Flipkart using Python. The script collects information about 5G mobile phones under ₹50,000, including product names, prices, descriptions, and ratings/reviews. The scraped data is stored in a structured format using Pandas and can be exported to Excel for further analysis.

## Features

* Scrapes multiple pages of Flipkart search results.
* Extracts:

  * Product Name
  * Price
  * Description
  * Ratings/Reviews
* Stores data in Pandas DataFrame.
* Exports data to Excel files.
* Uses BeautifulSoup for HTML parsing.
* Uses Requests for fetching web pages.

## Technologies Used

* Python
* Requests
* BeautifulSoup4
* Pandas
* OpenPyXL

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/flipkart-mobile-scraper.git
cd flipkart-mobile-scraper
```

Install required libraries:

```bash
pip install requests
pip install beautifulsoup4
pip install pandas
pip install openpyxl
```

## Project Structure

```text
flipkart-mobile-scraper/
│
├── webscrap.ipynb
├── README.md
└── output.xlsx
```

## How It Works

1. Sends HTTP requests to Flipkart search result pages.
2. Parses HTML content using BeautifulSoup.
3. Extracts mobile product information.
4. Stores extracted data in lists.
5. Converts data into a Pandas DataFrame.
6. Saves the results into an Excel file.

## Sample Data Fields

| Product     | Price   | Description            | Reviews |
| ----------- | ------- | ---------------------- | ------- |
| Mobile Name | ₹49,999 | Product Specifications | 4.5 ★   |

## Learning Outcomes

* Web Scraping Fundamentals
* HTML Parsing with BeautifulSoup
* Handling Multiple Web Pages
* Data Cleaning and Storage
* Exporting Data to Excel
* Data Analysis Preparation

## Disclaimer

This project is intended for educational and learning purposes only. Please respect Flipkart's Terms of Service and website policies before scraping data from the platform.

## Author

Swetha Eedumalli

B.Tech Student | Data Science & Machine Learning Enthusiast
