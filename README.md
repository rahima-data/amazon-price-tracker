# 🛒 Amazon Price Tracker

My second Python project! A web scraper that tracks Amazon product 
prices over time and saves them to a CSV file with the date.

## 🔍 What It Does
- Visits a real Amazon product page
- Scrapes the product title and current price
- Records today's date automatically
- Saves data to a CSV file — run daily to build price history!

## 🔧 Libraries Used
- `requests` - fetches the Amazon webpage
- `BeautifulSoup` - parses the HTML
- `pandas` - reads and displays price history
- `datetime` - records the date of each price check
- `lxml` - faster HTML parser for complex websites

## 🌟 What I Learned
- How to use HTTP headers to bypass bot detection
- Why websites block scrapers and how to handle it
- How to append data to CSV files over time
- How to use pandas DataFrames for the first time
- How status codes work (200, 404, 403)

## 📊 Sample Output
