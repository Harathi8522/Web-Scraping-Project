# Web-Scraping-Project
A hands-on project demonstrating web scraping techniques using Python. This repository includes scripts for extracting data from websites, cleaning and storing the data, and exporting it to structured formats like CSV or JSON.
# 📚 Book Web Scraper

A Python-based web scraping project using **BeautifulSoup** and **Pandas** to extract book data from [BooksToScrape.com](http://books.toscrape.com/), a sandbox website for practicing scraping techniques.

---

## 🚀 Project Features

- Scrapes **1000 books** across **50 pages**
- Extracts:
  - ✅ Title
  - ✅ Price
  - ✅ Star Rating
  - ✅ Direct Product Link
- Cleans data (e.g., converts prices to float, ratings to numbers)
- Exports to **CSV** for easy analysis
- Fully runnable in **Google Colab**

---

## 🛠 Tech Stack

- Python 3
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - HTML parsing
- [Pandas](https://pandas.pydata.org/) - Data handling and export
- [Requests](https://docs.python-requests.org/en/latest/) - HTTP requests
- [Google Colab](https://colab.research.google.com/) - Notebook execution

---

## 📂 How to Use

1. **Open Google Colab**
   - Upload the script or copy-paste the code
2. **Run the scraper**
   - Automatically fetches data from all pages
3. **View the data**
   - Displays the top rows in a DataFrame
4. **Download the CSV**
   - Cleaned dataset ready for analysis or ML tasks

---

## 📊 Sample Output

| Title                            | Price | Rating | Link                                      |
|----------------------------------|--------|--------|-------------------------------------------|
| A Light in the Attic            | 51.77  | 3      | http://...                                |
| Tipping the Velvet              | 53.74  | 1      | http://...                                |

---

## 🧹 Data Cleaning Steps

- Removed `£` sign from prices and converted to `float`
- Converted ratings from words (`One`, `Two`, etc.) to numeric values (`1` to `5`)

---

## 📈 Optional Analysis Ideas

- Filter books by rating or price
- Find average price per rating
- Visualize number of books by rating with `seaborn` or `matplotlib`

---

## 🔐 Disclaimer

This project is for **educational purposes** only. The website used is a **practice site** designed for web scraping experiments.

---

## 🙌 Acknowledgements

Thanks to [BooksToScrape.com](http://books.toscrape.com/) for providing a safe environment for scraping practice.

---





