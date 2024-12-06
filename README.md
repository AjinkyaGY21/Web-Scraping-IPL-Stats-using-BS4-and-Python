# 🏏 IPL Statistics Web Scraper

## 📝 Project Description

A CLI application to extract player and team statistics from the official Indian Premier League (IPL) website. This Python-based web scraper allows users to fetch detailed cricket statistics from 2008 to the latest edition.

## ✨ Features

- 🗓️ Select years from 2008 to the current year
- 📊 Extract multiple types of statistical data
- 💾 Save data in CSV format
- 🖥️ Easy-to-use Command Line Interface

## 🛠️ Prerequisites

### 🐍 Required Python Version
- Python 3.7+

### 📦 Dependencies
- beautifulsoup4
- requests
- PyInquirer
- pandas
- numpy

## 🚀 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AjinkyaGY21/Web-Scraping-IPL-Stats-using-BS4-and-Python
   ```

2. **Create Virtual Environment** (Optional but Recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 📋 Requirements File (requirements.txt)
Create a `requirements.txt` file with the following content:
```
beautifulsoup4==4.9.3
requests==2.25.1
PyInquirer==1.0.3
pandas==1.2.4
numpy==1.20.2
```

## 🖥️ Usage

Run the scraper:
```bash
python scrapper.py
```

### 🎮 Interactive Prompts
1. Select the year(s) you want to scrape
2. Choose the type of statistics you're interested in
3. The data will be automatically saved as CSV files

## 🔍 How It Works

1. Fetches available years and statistics from IPL website
2. Allows user to select specific years and stat types
3. Scrapes data using BeautifulSoup
4. Saves extracted data in CSV format

## 🛡️ Error Handling

- Graceful exit on keyboard interrupts (CTRL+C)
- Handles various edge cases in web scraping


## 🙌 Acknowledgments

- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
- [Requests Library](https://docs.python-requests.org/)
- [PyInquirer](https://github.com/CITGuru/PyInquirer)
