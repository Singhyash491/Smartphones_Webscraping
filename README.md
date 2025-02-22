# 📱 Smartphones Web Scraping  

## 📌 Overview  
This project involves web scraping smartphone data from **Smartprix** using Selenium and BeautifulSoup. The scraped data includes specifications like price, processor, RAM, battery, display, and camera details, which are stored in a structured format for further analysis.  

## 🛠 Problem Statement  
Smartphone buyers often find it challenging to compare specifications across multiple devices. This project aims to automate data extraction from **Smartprix**, creating a dataset that can be used for further analysis and decision-making.  

## 🔍 Solution Approach  
1. **Selenium** is used to load the website, apply filters, and scroll through the listings.  
2. The **HTML content is saved** for later processing.  
3. **BeautifulSoup** extracts smartphone details such as model, price, processor, RAM, and other key features.  
4. The extracted data is stored in a **pandas DataFrame** and exported as a CSV file.  

## 📊 Key Findings  
- Successfully scraped smartphone specifications from Smartprix.  
- The script extracts multiple attributes like price, processor, RAM, and battery capacity.  
- The dataset is well-structured and ready for further **data cleaning** and **exploratory data analysis (EDA)**.  

## 🛠 Libraries & Tools Used  
- **Selenium** - Web automation  
- **BeautifulSoup** - HTML parsing  
- **Pandas** - Data handling  
- **NumPy** - Data manipulation  

## ⚙ How It Works  
1. **Run `smartprix.py`**  
   - Launches a Chrome browser, applies filters, and scrolls through the webpage.  
   - Saves the **HTML source code** as `smartprix.html`.  
2. **Run `smartphones.ipynb`**  
   - Reads `smartprix.html`, extracts smartphone data, and stores it in a **DataFrame**.  
   - Saves the cleaned dataset as `Scrapped_data.csv`.  

## 🚀 How to Run the Project  
### **1️⃣ Install Dependencies**  
```bash
pip install selenium beautifulsoup4 pandas numpy
Run the Scraper (Extract HTML)
