<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="100%" height="100%">
    <defs>
      <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#0f172a" />
        <stop offset="50%" stop-color="#1e293b" />
        <stop offset="100%" stop-color="#0284c7" />
      </linearGradient>
      <linearGradient id="accent-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#38bdf8" />
        <stop offset="100%" stop-color="#818cf8" />
      </linearGradient>
    </defs>
    
    <!-- Background -->
    <rect width="1200" height="320" rx="16" fill="url(#bg-grad)" />
    
    <!-- Decorative Grid Overlay -->
    <g opacity="0.08" stroke="#ffffff" stroke-width="1">
      <line x1="0" y1="80" x2="1200" y2="80" />
      <line x1="0" y1="160" x2="1200" y2="160" />
      <line x1="0" y1="240" x2="1200" y2="240" />
      <line x1="300" y1="0" x2="300" y2="320" />
      <line x1="600" y1="0" x2="600" y2="320" />
      <line x1="900" y1="0" x2="900" y2="320" />
    </g>
    
    <!-- Glowing Accent Bar -->
    <rect x="80" y="65" width="8" height="190" rx="4" fill="url(#accent-grad)" />
    
    <!-- Main Content -->
    <text x="110" y="115" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="40" font-weight="800" fill="#ffffff" letter-spacing="1">
      TWITTER DATA PIPELINE &amp; NLP
    </text>
    
    <text x="110" y="155" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="20" font-weight="500" fill="#38bdf8" letter-spacing="0.5">
      End-to-End ETL, Text Preprocessing &amp; Sentiment Analytics
    </text>

    <!-- Subtitle / Key Highlights -->
    <text x="110" y="215" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="16" font-weight="400" fill="#94a3b8">
      • Automated Extraction  • Feature Engineering  • NLTK Preprocessing  • Anonymized Data Architecture
    </text>
    
    <!-- Tech Stack Indicators -->
    <g transform="translate(110, 235)">
      <rect x="0" y="0" width="85" height="26" rx="6" fill="#0369a1" opacity="0.6"/>
      <text x="42" y="17" font-family="sans-serif" font-size="12" font-weight="600" fill="#e0f2fe" text-anchor="middle">PYTHON</text>

      <rect x="95" y="0" width="85" height="26" rx="6" fill="#0369a1" opacity="0.6"/>
      <text x="137" y="17" font-family="sans-serif" font-size="12" font-weight="600" fill="#e0f2fe" text-anchor="middle">PANDAS</text>

      <rect x="190" y="0" width="85" height="26" rx="6" fill="#0369a1" opacity="0.6"/>
      <text x="232" y="17" font-family="sans-serif" font-size="12" font-weight="600" fill="#e0f2fe" text-anchor="middle">NLTK</text>

      <rect x="285" y="0" width="85" height="26" rx="6" fill="#0369a1" opacity="0.6"/>
      <text x="327" y="17" font-family="sans-serif" font-size="12" font-weight="600" fill="#e0f2fe" text-anchor="middle">SQL / ETL</text>
    </g>
  </svg>

  <br><br>

  [![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
  [![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
  [![NLTK](https://img.shields.io/badge/NLTK-NLP%20Preprocessing-green?style=for-the-badge)](https://www.nltk.org/)
  [![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

</div>

---

## 📌 Overview
פרויקט זה מממש צינור נתונים (Data Pipeline) מקצה לקצה לאיסוף, ניקוי, עיבוד והכנה של נתוני ציוצים מ-Twitter (X) עבור ניתוחי סנטימנט ומדדי מעורבות (Engagement Rate).

הפרויקט מורכב משני שלבים מרכזיים ומייצר שני מאגרי נתונים ייעודיים:
1. **Raw Dataset (`raw_tweets_dataset.csv`)** – נתונים גולמיים הכוללים מטא-דאטה מלאה, מידע על משתמשים ומאפייני ציוצים.
2. **Processed Dataset (`processed_tweets_dataset.csv`)** – נתונים מעובדים ועוברים הנדסת תכונות (Feature Engineering), ניקוי טקסט מתקדם (NLP - Tokenization, Lemmatization, Stop-Words removal) וחישוב מדדים ייעודיים.

---

## 🛠️ Architecture & Tech Stack
* **Language:** Python
* **Data Processing & ETL:** Pandas, NumPy
* **NLP & Text Normalization:** NLTK (Tokenizer, WordNetLemmatizer, Stopwords), Regex
* **Data Hashing & Security:** Hashlib (Anonymized User IDs)

---

## 📁 Repository Structure
```text
.
├── raw_tweets_dataset.csv        # Raw extracted Twitter dataset
├── processed_tweets_dataset.csv  # Cleaned & processed dataset ready for analysis
├── main_pipeline.py              # Main execution script
├── README.md                     # Project documentation
└── requirements.txt              # Project dependencies

## Overview#

Twitter Sentiment & Analytics - #Israel
An end-to-end Data Engineering, NLP, and Business Intelligence project analyzing over 4 years of Twitter data centered around  #Israel. This project demonstrates a full data pipeline: scraping social media data, applying Natural Language Processing (NLP) preprocessing, performing advanced SQL queries, and designing interactive Power BI dashboards
---

##  Architecture & Tech Stack
* **Language:** Python
* **Data Processing & ETL:** Pandas, NumPy
* **NLP & Text Normalization:** NLTK (Tokenizer, WordNetLemmatizer, Stopwords), Regex
* **Data Hashing & Security:** Hashlib (Anonymized User IDs)

---

##  Project Overview

Understanding public perception and engagement trends on social media requires processing large volumes of unstructured data. This project collects, cleans, analyzes, and visualizes Twitter data related to Israel between **2019 and 2023** to uncover sentiment patterns, key conversation drivers, geographical distribution, and high-impact users.

---

##  Tech Stack & Tools

* **Programming & Scraping:** Python (`snscrape`, `pandas`, `numpy`)
* **NLP & Text Processing:** `NLTK` (Lemmatization, Stop-Words), `re` (Regex), `emot` (Emoji Extraction)
* **Database & Querying:** Microsoft SQL Server (Advanced SQL, Recursive CTEs, Window Functions)
* **Data Visualization & BI:** Power BI (Multi-page Dashboards, DAX, Custom Filters)

---

##  Key Features & Pipeline Architecture

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

##  Key Insights Highlights

* **Sentiment Breakdown:** 37% Positive, 43% Neutral, and 20% Negative across the dataset.
* **Top Co-occurring Themes:** High volume of paired discussions involving Middle Eastern geopolitics (*#Palestine*, *#Iran*, *#Gaza*, *#Ukraine*).
* **User Reach:** Verified users account for a small percentage of total posters but drive a significant portion of overall retweets and likes.

---

## 📁 Repository Structure


├── Scripts/
│   ├── twitter_scraper_and_nlp.py
│   └── sql_queries.sql
├── Dashboards/
│   └── Twitter_Sentiment_Analysis.pbix
└── README.md
