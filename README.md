<div align="center">
<p align="center">
  <img src="./header.svg" alt="Twitter Data Pipeline Banner" width="100%">
</p>

# 📊 Twitter Data Pipeline & Sentiment Analysis
### End-to-End ETL, Text Preprocessing & Sentiment Analytics

---

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NLTK](https://img.shields.io/badge/NLTK-NLP%20Preprocessing-green?style=for-the-badge)](https://www.nltk.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

---

</div>


# Twitter Sentiment & Analytics - #Israel

An end-to-end Data Engineering, NLP, and Business Intelligence project analyzing over 4 years of Twitter data centered around **#Israel**. 

This project demonstrates a full data pipeline: scraping social media data, applying Natural Language Processing (NLP) preprocessing, performing advanced SQL queries, and designing interactive Power BI dashboards.

---

## 📌 Project Overview

Understanding public perception and engagement trends on social media requires processing large volumes of unstructured data. This project collects, cleans, analyzes, and visualizes Twitter data related to Israel between **2019 and 2023** to uncover sentiment patterns, key conversation drivers, geographical distribution, and high-impact users.

---

## 🛠 Tech Stack & Tools

* **Programming & Scraping:** Python (`snscrape`, `pandas`, `numpy`)
* **NLP & Text Processing:** `NLTK` (Lemmatization, Stop-Words), `re` (Regex), `emot` (Emoji Extraction)
* **Database & Querying:** Microsoft SQL Server (Advanced SQL, Recursive CTEs, Window Functions)
* **Data Visualization & BI:** Power BI (Multi-page Dashboards, DAX, Custom Filters)

---

## 🚀 Key Features & Pipeline Architecture

### 1. Data Collection & Scraping
* Developed an automated Python scraping pipeline using `snscrape` to extract over **109K tweets** spanning 4+ years.
* Extracted core metadata: Tweet ID, Content, User Handles, Engagement Metrics (Likes, Retweets, Replies, Quotes), Follower Counts, Location, and Verification Status.

### 2. Data Preprocessing & NLP
* **Data Cleaning:** Handled missing values, removed duplicates, non-English characters, URLs, and mentions.
* **Text Normalization:** Applied **Lemmatization** via `NLTK` to reduce words to their dictionary base forms, extracted emojis, and filtered out standard and domain-specific stop words.
* **Feature Engineering:** Calculated a custom **Engagement Rate** metric and engineered temporal attributes (Hour, Day, Month, Year, Day of Week).

### 3. Database Engineering & Advanced SQL
* Loaded cleaned datasets into MS SQL Server for deep analytical querying.
* Wrote **Recursive CTEs** to parse and split complex comma-separated hashtag lists.
* Utilized **Window Functions** (`ROW_NUMBER`, `PARTITION BY`) to rank top hashtags by country, month, and year.
* Analyzed co-occurring hashtag pairs (e.g., *#Israel & #Palestine*, *#Israel & #Iran*).

### 4. Interactive Power BI Dashboards
* **Executive Summary:** Overview of total tweets, sentiment distribution (Positive, Negative, Neutral), and device sources.
* **Geographical & Temporal Insights:** Tweet volume mapped by country and engagement trends across days and months.
* **Hashtag & Word Analysis:** Frequency counts of top terms, hashtag co-occurrence analysis, and country-level hashtag rankings.
* **User & Engagement Analytics:** Tracking most active users, verified vs. unverified profiles, and correlation between follower count and engagement.

---

## 📊 Key Insights Highlights

* **Sentiment Breakdown:** 37% Positive, 43% Neutral, and 20% Negative across the dataset.
* **Top Co-occurring Themes:** High volume of paired discussions involving Middle Eastern geopolitics (*#Palestine*, *#Iran*, *#Gaza*, *#Ukraine*).
* **User Reach:** Verified users account for a small percentage of total posters but drive a significant portion of overall retweets and likes.

---

## 📁 Repository Structure

```text
├── Data/
│   ├── raw_tweets.csv
│   └── processed_tweets.csv
├── Scripts/
│   ├── twitter_scraper_and_nlp.py
│   └── sql_queries.sql
├── Dashboards/
│   └── Twitter_Sentiment_Analysis.pbix
└── README.md
