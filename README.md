# 🏘️ Study on Rental Properties in Hyderabad (Makaan Data)

This project is a full data pipeline starting from **web scraping real-estate data** from [makaan.com](https://www.makaan.com) to performing **exploratory data analysis (EDA)** on rental properties in Hyderabad. The aim is to discover insights into rent prices, property types, and location-based trends to assist renters, buyers, and investors in making data-driven decisions.

---

## 🔍 Problem Statement

Hyderabad is emerging as a major IT and real-estate hub. This project addresses:

- How can we collect real-time rental property data from online portals?
- What are the key factors influencing rental prices?
- How does rent vary by location, BHK type, and furnishing?
- What trends can be derived from online property listings?

---

## 🕸️ Web Scraping Phase

The data was collected through **custom Python-based web scraping** using `requests`, `BeautifulSoup`, and `pandas`. The scraper extracted details from [makaan.com](https://www.makaan.com/hyderabad-property/rent-property-in-hyderabad), including:

- Property title
- Price (Rent)
- BHK
- Locality / Location
- Area (sq. ft.)
- Furnishing status
- Number of bathrooms
- Posted by (Owner, Dealer, Builder)

> ⚠️ Note: The scraper respects makaan.com’s terms of service and is intended for educational purposes only.

---

## 🧰 Tools & Technologies

- **Python** 🐍
- `requests`, `BeautifulSoup` – Web scraping
- `pandas`, `numpy` – Data wrangling
- `matplotlib`, `seaborn` – Visualizations
- **Jupyter Notebook** – Analysis and reporting

---

## 📊 Key Insights

- **High-demand areas** like Gachibowli, Kondapur, and Hitech City command premium rent.
- **2BHK and 3BHK** units are most common in listings.
- **Furnishing** and **posted by** (owner vs builder) play a key role in pricing.
- Large variance in price distribution, often influenced by luxury properties.

---

## 📈 Visualizations Include

- Distribution of properties by BHK and locality
- Rent variation via boxplots and bar graphs
- Correlation heatmaps for numeric columns
- Pie charts for categorical features (furnishing, posted_by, etc.)

---
