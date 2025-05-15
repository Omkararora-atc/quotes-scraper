# ✨ Quotes Scraper

A lightweight Python web scraper that extracts quotes, authors, and tags from the website [Quotes to Scrape](https://quotes.toscrape.com/) and saves the data to a CSV file.

---

## 🚀 Features

✅ Scrapes quotes from **multiple pages (1–10)**  
✅ Extracts:
- Quote text
- Author name
- Author profile link
- Tags  

✅ Saves data into a **CSV file** (`new_quotes.csv`)  
✅ Displays a **progress bar** with `tqdm`  

---

## 🛠 Tech Stack

- 🐍 Python 3.x  
- 🌐 `requests` – for fetching HTML content  
- 🥣 `BeautifulSoup` (from `bs4`) – for HTML parsing  
- 📊 `pandas` – for organizing and exporting data  
- 📈 `tqdm` – for progress visualization  

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Omkararora-atc/quotes-scraper.git
   cd quotes-scraper
2. **Install dependencies**
    ```bash
   pip install requests beautifulsoup4 pandas tqdm
3. **▶️ Usage
     Run the scraper using**
    ```bash
   QuotesToScrape.py
After execution, a file named new_quotes.csv will be generated containing the scraped data.

## 🧠 Code Overview
Here's what the script does:

- Loops through pages 1–10 of the target website

- Sends HTTP requests and parses HTML

- Extracts:

- Quote text

- Author

- Author profile URL

- Tags

- Adds a full author URL

- Saves all data to a CSV file

## 🤝 Contributing
Got ideas? Found a bug?
Feel free to open an issue or submit a pull request to improve this scraper.

## 👤 Author
 Omkar Arora

## 📄 License
This project is licensed under the MIT License.
See the LICENSE file for details.

