# 🏡 Avito Web Scraper

This project is a web scraper built using **Python** and **Selenium** to collect data on apartments listed for sale on [Avito.ma](https://www.avito.ma/fr/maroc/appartements-%C3%A0_vendre). The script navigates through listing pages, opens each apartment ad, and extracts detailed information such as title, price, location, property details, and description.

---

## 🔍 Features

- Scrapes apartment listings from multiple pages on Avito.ma.
- Extracts detailed attributes like:
  - Title
  - Price
  - City & Sector
  - Type & Floor
  - Surface Area, Age of Property
  - Number of Rooms (salons, bedrooms, bathrooms)
  - Syndic Fees
  - Description
- Saves data in a clean CSV format (`Appartements.csv`)

---

## 🛠️ Requirements

- Python 3.x
- Google Chrome
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)
- Required Python packages:
  ```bash
  pip install selenium
