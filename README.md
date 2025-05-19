# 🏒 Hockey Stats Web Scraper

This project is a Python-based web scraper that extracts hockey team statistics from [Scrape This Site](https://www.scrapethissite.com/pages/forms/). It demonstrates how to automate data gathering using `requests`, `BeautifulSoup`, and `pandas`. The scraper collects structured data from multiple pages using pagination and stores it in a clean DataFrame, which is then exported to a `.csv` file.

---

## 📌 Project Overview

- 🔎 Scrapes structured data from a live website
- 🔁 Handles multiple pages via pagination
- 🧽 Parses and cleans HTML content
- 📊 Stores data in a `pandas` DataFrame
- 💾 Saves data to a CSV file for analysis

---

## 🛠️ Tools & Technologies

- **Python** (via Google Colab)
- [Requests](https://docs.python-requests.org/en/latest/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Pandas](https://pandas.pydata.org/)
- Google Colab (for writing and running the notebook)

---

## 📂 Files Included

| File Name              | Description                                      |
|------------------------|--------------------------------------------------|
| `hockey_scraper.ipynb` | Main Jupyter Notebook with web scraping code     |
| `all_hockey_stats.csv` | Output CSV file containing all scraped data      |
| `README.md`            | This project description                         |

---

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/hockey-webscraper.git
cd hockey-webscraper
```

---

## Open the Notebook
- You can open hockey_scraper.ipynb directly in Google Colab or Jupyter Notebook.

## Run All Cells
Ensure all necessary libraries are installed. Run all cells to:
- Fetch data from each season
- Store it in a DataFrame
- Export the final result to a .csv file

## 📈 Future Improvements
- Add visualizations using matplotlib/seaborn
- Scrape other datasets from the same site
- Add data cleaning/validation steps
- Automate daily/weekly scraping with scheduling

## 👤 Author
Joseph
Python & Data Science Enthusiast
GitHub:@Joseph89155

## 📃 License
This project is licensed under the MIT License.
