<div align="center">
<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 200" width="100%" height="100%">
    <defs>
      <!-- רקע מדורג כהה ומודרני -->
      <linearGradient id="rect-bg" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#090d16" />
        <stop offset="40%" stop-color="#0f172a" />
        <stop offset="100%" stop-color="#1e1b4b" />
      </linearGradient>

      <!-- דירוג צבע לבר ההדגשה העליון -->
      <linearGradient id="top-bar-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#0284c7" />
        <stop offset="50%" stop-color="#6366f1" />
        <stop offset="100%" stop-color="#a855f7" />
      </linearGradient>

      <!-- דירוג צבע לטקסט הראשי -->
      <linearGradient id="text-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#38bdf8" />
        <stop offset="100%" stop-color="#818cf8" />
      </linearGradient>
    </defs>

    <!-- רקע מלבני מוארך -->
    <rect width="1200" height="200" rx="12" fill="url(#rect-bg)" stroke="#1e293b" stroke-width="2"/>

    <!-- פס אופקי עליון מואר -->
    <rect x="0" y="0" width="1200" height="6" rx="3" fill="url(#top-bar-grad)" />

    <!-- רשת רקע עדינה (Grid Lines) -->
    <g opacity="0.05" stroke="#ffffff" stroke-width="1">
      <line x1="0" y1="50" x2="1200" y2="50" />
      <line x1="0" y1="100" x2="1200" y2="100" />
      <line x1="0" y1="150" x2="1200" y2="150" />
      <line x1="200" y1="0" x2="200" y2="200" />
      <line x1="400" y1="0" x2="400" y2="200" />
      <line x1="600" y1="0" x2="600" y2="200" />
      <line x1="800" y1="0" x2="800" y2="200" />
      <line x1="1000" y1="0" x2="1000" y2="200" />
    </g>

    <!-- אייקון נתונים אבסטרקטי (צד שמאל) -->
    <g transform="translate(60, 55)">
      <rect x="0" y="30" width="12" height="60" rx="3" fill="#0284c7" opacity="0.8"/>
      <rect x="20" y="10" width="12" height="80" rx="3" fill="#38bdf8" />
      <rect x="40" y="45" width="12" height="45" rx="3" fill="#6366f1" opacity="0.9"/>
      <rect x="60" y="20" width="12" height="70" rx="3" fill="#a855f7" />
    </g>

    <!-- כותרת ראשית -->
    <text x="160" y="90" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="38" font-weight="800" fill="#ffffff" letter-spacing="1">
      TWITTER DATA PIPELINE &amp; NLP ANALYTICS
    </text>

    <!-- כותרת משנה -->
    <text x="160" y="128" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="18" font-weight="500" fill="url(#text-grad)" letter-spacing="0.5">
      Automated ETL • Text Preprocessing • Sentiment &amp; Engagement Analytics
    </text>

    <!-- תגיות טכנולוגיה קומפקטיות בתחתית -->
    <g transform="translate(160, 148)">
      <rect x="0" y="0" width="110" height="22" rx="4" fill="#0f172a" stroke="#0284c7" stroke-width="1"/>
      <text x="55" y="15" font-family="sans-serif" font-size="11" font-weight="600" fill="#38bdf8" text-anchor="middle">PYTHON 3.10+</text>

      <rect x="120" y="0" width="80" height="22" rx="4" fill="#0f172a" stroke="#6366f1" stroke-width="1"/>
      <text x="160" y="15" font-family="sans-serif" font-size="11" font-weight="600" fill="#818cf8" text-anchor="middle">PANDAS</text>

      <rect x="210" y="0" width="70" height="22" rx="4" fill="#0f172a" stroke="#a855f7" stroke-width="1"/>
      <text x="245" y="15" font-family="sans-serif" font-size="11" font-weight="600" fill="#c084fc" text-anchor="middle">NLTK</text>

      <rect x="290" y="0" width="110" height="22" rx="4" fill="#0f172a" stroke="#38bdf8" stroke-width="1"/>
      <text x="345" y="15" font-family="sans-serif" font-size="11" font-weight="600" fill="#7dd3fc" text-anchor="middle">SQL &amp; ETL</text>
    </g>
  </svg>
</div>
# 📊 Twitter Data Pipeline & Sentiment Analysis
### End-to-End ETL, Text Preprocessing & Sentiment Analytics

---

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NLTK](https://img.shields.io/badge/NLTK-NLP%20Preprocessing-green?style=for-the-badge)](https://www.nltk.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

---

</div>


---


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
