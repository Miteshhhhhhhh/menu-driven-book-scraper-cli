# Menu-Driven Book Scraper CLI

A Python CLI tool to scrape books.toscrape.com with modular menu options.

## Features
- 4 menu options: Scrape Books, Analyze by Price, Top Rated Books, Export Summary
- Scrapes name, price, rating from books.toscrape.com
- Exports 3 separate Excel reports: all_books.xlsx, top_rated_books.xlsx, book_summary.xlsx
- Auto-opens Excel files without conflicts using os.startfile()
- Guard clauses to prevent errors on empty data

## How to Run
```bash
pip install -r requirements.txt
python book_scraper.py