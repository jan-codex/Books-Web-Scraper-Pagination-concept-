# 📚 Books-Web-Scraper-Pagination-concept-

This Python script scrapes book information from the [Books to Scrape](http://books.toscrape.com/) website, specifically from the **Mystery** category. It handles **pagination automatically**, gathering book data from **all pages** in the category.

## 🛠️ Features

- Scrapes all paginated pages in the **Mystery** category.
- Extracts the following data for each book:
  - Title
  - Price
  - Stock availability
  - Image URL
  - Rating
  - Product detail page URL
- Dynamically detects the number of pages.
- Saves the data into a well-structured CSV file.

## 🐍 Technologies Used

- Python 3
- `lxml` for HTML parsing
- `XPath` for precise element selection
- `math` for calculating total pages
- `csv` for writing data

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jan-codex/Books-Web-Scraper-Pagination-concept-.git
   cd Books-Web-Scraper-Pagination-concept-

