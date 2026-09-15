# Premier League Players Data Scraping

A Python-based web scraping project that collects **Premier League player statistics**, focusing on players with the highest numbers of **goals and assists**. The project uses **BeautifulSoup, Selenium, Pandas, and Matplotlib** for data extraction, processing, analysis, and visualization.

## 🚀 Project Overview

This project demonstrates how web scraping can be used to collect and analyze football statistics from the Premier League.

The main objectives are to:

* Scrape Premier League player statistics from the web
* Extract players with the highest goals and assists
* Handle dynamically loaded web content using Selenium
* Parse HTML data using BeautifulSoup
* Convert scraped data into Pandas DataFrames
* Analyze player performance
* Create visualizations to compare players

## 🛠️ Technologies Used

* **Python**
* **BeautifulSoup** – HTML parsing and data extraction
* **Selenium** – Browser automation and dynamic content scraping
* **Pandas** – Data cleaning and DataFrame manipulation
* **Matplotlib** – Data visualization
* **WebDriver** – Automated browser interaction

## 📊 Features

### Player Statistics

The scraper collects Premier League player performance data, including:

* Player names
* Goals
* Assists
* Other available performance statistics

### Data Processing

The scraped information is transformed into structured **Pandas DataFrames**, making the data easier to analyze and manipulate.

### Data Visualization

The project generates graphs to visualize player performance, including comparisons of:

* Top goal scorers
* Top assist providers
* Player performance statistics

## 🔄 Workflow

```text
Premier League Website
        ↓
     Selenium
        ↓
 Dynamic Web Content
        ↓
   BeautifulSoup
        ↓
   Data Extraction
        ↓
      Pandas
        ↓
 Data Cleaning & Analysis
        ↓
   Matplotlib
        ↓
    Visualization
```

## 📁 Project Structure

```text
Premier-League-Players-Data-Scraping/
│
├── scraping.py
├── analysis.py
├── visualization.py
├── data/
│   └── scraped_data.csv
├── graphs/
│   └── player_statistics.png
├── requirements.txt
└── README.md
```

> The actual file structure may vary depending on the implementation.

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Or install the main packages manually:

```bash
pip install beautifulsoup4 selenium pandas matplotlib
```

### 3. Run the scraper

```bash
python scraping.py
```

The scraper will collect the available player statistics and process them into structured data.

## 📈 Results

The collected data can be used to identify and compare the Premier League's leading players based on goals and assists.

The project also produces visualizations that provide a quick overview of player performance.

## 🎯 Learning Outcomes

Through this project, I explored:

* Web scraping with Python
* HTML parsing with BeautifulSoup
* Browser automation with Selenium
* Handling dynamically rendered webpages
* Data cleaning and transformation with Pandas
* Exploratory data analysis
* Data visualization with Matplotlib

## 📌 Future Improvements

* Scrape additional player statistics
* Automatically update the dataset
* Add more advanced visualizations
* Build an interactive dashboard
* Compare players across different seasons
* Store scraped data in a database
* Automate scheduled data collection

## 👨‍💻 Author

**Rahman Saif**

This project was created as a practical exploration of **Python web scraping, data analysis, and visualization**.
