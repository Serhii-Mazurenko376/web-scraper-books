# 📚 Python Web Scraper: Books to Excel

This project is a simple and clean web scraper built in Python using `requests`, `BeautifulSoup`, and `pandas`. It scrapes book data from the public site [Books to Scrape](http://books.toscrape.com/) and exports it to an Excel file — all using **Google Colab on an iPad**.

---

## 🔍 What It Does

- Fetches the homepage of [books.toscrape.com](http://books.toscrape.com/)
- Extracts:
  - Book title
  - Price
  - Star rating
- Stores all results in a structured table
- Exports the results to an `.xlsx` file

---

## 🚀 How to Run

### ▶️ 1. Open the Colab notebook:
[Open in Google Colab](https://colab.research.google.com/github/Serhii-Mazurenko376/web-scraper-books/blob/main/book_scraper.ipynb)

### 📦 2. Required Libraries:
Installed directly in the notebook:
```python```
!pip install requests beautifulsoup4 pandas openpyxl

📎 License

This project is licensed for educational use only and uses a public demo scraping site.
