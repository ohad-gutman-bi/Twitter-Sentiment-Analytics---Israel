<div align="center">
<img width="1945" height="87" alt="banner" src="https://github.com/user-attachments/assets/ab491274-b1a6-4b41-888d-1426b0940af8" />

### End-to-End ETL, Text Preprocessing, Advanced SQL & Power BI Analytics

---

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NLTK](https://img.shields.io/badge/NLTK-NLP%20Preprocessing-green?style=for-the-badge)](https://www.nltk.org/)
[![SQL Server](https://img.shields.io/badge/MS%20SQL%20Server-Advanced%20Queries-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](https://www.microsoft.com/sql-server)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboards%20%26%20DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)

---

</div>

##  Project Overview

Understanding public perception and engagement trends on social media requires processing large volumes of unstructured data. This project collects, cleans, analyzes, and visualizes Twitter data related to Israel between **2019 and 2023** to uncover sentiment patterns, key conversation drivers, geographical distribution, and high-impact users.

---

##  Tech Stack & Tools

- **Data Processing & Pipeline:** Python (`pandas`, `numpy`, `re`)
- **NLP & Text Processing:** `NLTK` (Tokenization, Lemmatization, Stop-Words), `emot` (Emoji Extraction)
- **Database & Querying:** Microsoft SQL Server (Advanced SQL, Recursive CTEs, Window Functions)
- **Data Visualization & BI:** Power BI (Multi-page Dashboards, DAX, Custom Filters)

---

##  Key Features & Pipeline Architecture

### 1. Data Collection & Extraction
- Processed a dataset of over **109K tweets** spanning 4+ years (2019–2023).
- Extracted core metadata: Tweet ID, Content, User Handles, Engagement Metrics (Likes, Retweets, Replies, Quotes), Follower Counts, Location, and Verification Status.

### 2. Data Preprocessing & NLP
- **Data Cleaning:** Handled missing values, removed duplicates, non-English characters, URLs, and mentions.
- **Text Normalization:** Applied **Lemmatization** via `NLTK` to reduce words to their dictionary base forms, extracted emojis, and filtered out standard and domain-specific stop words.
- **Feature Engineering:** Calculated a custom **Engagement Rate** metric and engineered temporal attributes (Hour, Day, Month, Year, Day of Week).

### 3. Database Engineering & Advanced SQL
- Loaded cleaned datasets into MS SQL Server for deep analytical querying.
- Wrote **Recursive CTEs** to parse and split complex comma-separated hashtag lists.
- Utilized **Window Functions** (`ROW_NUMBER`, `PARTITION BY`) to rank top hashtags by country, month, and year.
- Analyzed co-occurring hashtag pairs (e.g., *#Israel & #Palestine*, *#Israel & #Iran*).

### 4. Interactive Power BI Dashboards
- **Executive Summary:** Overview of total tweets, sentiment distribution (Positive, Negative, Neutral), and device sources.
- **Geographical & Temporal Insights:** Tweet volume mapped by country and engagement trends across days and months.
- **Hashtag & Word Analysis:** Frequency counts of top terms, hashtag co-occurrence analysis, and country-level hashtag rankings.
- **User & Engagement Analytics:** Tracking most active users, verified vs. unverified profiles, and correlation between follower count and engagement.

---

##  Key Insights Highlights

- **Sentiment Breakdown:** 37% Positive, 43% Neutral, and 20% Negative across the dataset.
- **Top Co-occurring Themes:** High volume of paired discussions involving Middle Eastern geopolitics (*#Palestine*, *#Iran*, *#Gaza*, *#Ukraine*).
- **User Reach:** Verified users account for a small percentage of total posters but drive a significant portion of overall retweets and likes.

---
## 📊 Power BI Dashboard Overview

<p align="center">
  <img width="2075" height="1200" alt="Twitter sentiment analysis_Project_pdf-page-001" src="https://github.com/user-attachments/assets/061964d2-9d64-4726-8bf0-e92f398e9183" />

</p>
<p align="center">
  <img width="2075" height="1200" alt="Twitter sentiment analysis_Project_pdf-page-004" src="https://github.com/user-attachments/assets/a5c53e1a-5cda-45c5-a856-83db7fbc2c15" />

</p>


##  Repository Structure


├── Scripts/
│   ├── twitter_nlp_pipeline.py
│   └── sql_queries.sql
├── Dashboards/
│   └── Twitter_Sentiment_Analysis.pbix
└── README.md
