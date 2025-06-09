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


## Sample Output

| Title                                           | Price  | Stock    | Image URL                                                                                                                                                            | Rating | URL                                                                                                     |
| ----------------------------------------------- | ------ | -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ | ------------------------------------------------------------------------------------------------------- |
| Sharp Objects                                   | £47.82 | In stock | [http://books.toscrape.com/media/cache/32/51/3251cf3a3412f53f339e42cac2134093.jpg](http://books.toscrape.com/media/cache/32/51/3251cf3a3412f53f339e42cac2134093.jpg) | Four   | [Link](http://books.toscrape.com/catalogue/sharp-objects_997/index.html)                                |
| In a Dark, Dark Wood                            | £19.63 | In stock | [http://books.toscrape.com/media/cache/23/85/238570a1c284e730dbc737a7e631ae2b.jpg](http://books.toscrape.com/media/cache/23/85/238570a1c284e730dbc737a7e631ae2b.jpg) | One    | [Link](http://books.toscrape.com/catalogue/in-a-dark-dark-wood_963/index.html)                          |
| The Past Never Ends                             | £56.50 | In stock | [http://books.toscrape.com/media/cache/89/b8/89b850edb01851a91f64ba114b96acb6.jpg](http://books.toscrape.com/media/cache/89/b8/89b850edb01851a91f64ba114b96acb6.jpg) | Four   | [Link](http://books.toscrape.com/catalogue/the-past-never-ends_942/index.html)                          |
| A Murder in Time                                | £16.64 | In stock | [http://books.toscrape.com/media/cache/11/aa/11aaad48b5f15e262456ca65294084da.jpg](http://books.toscrape.com/media/cache/11/aa/11aaad48b5f15e262456ca65294084da.jpg) | One    | [Link](http://books.toscrape.com/catalogue/a-murder-in-time_877/index.html)                             |
| The Murder of Roger Ackroyd (Hercule Poirot #4) | £44.10 | In stock | [http://books.toscrape.com/media/cache/29/fe/29fe70b1b2e5a9ba61d4bd331255e19e.jpg](http://books.toscrape.com/media/cache/29/fe/29fe70b1b2e5a9ba61d4bd331255e19e.jpg) | Four   | [Link](http://books.toscrape.com/catalogue/the-murder-of-roger-ackroyd-hercule-poirot-4_852/index.html) |


