# 🌐 Website Performance Dashboard — Power BI

An interactive Power BI dashboard analysing website performance metrics across 5,870 visitor sessions, covering bounce rates, conversion rates, traffic sources, visitor behaviour, and geographic distribution.

---

## 📌 Project Overview

This project transforms raw website analytics data into a fully interactive dashboard that helps identify trends in user behaviour, traffic performance, and conversion efficiency across different visitor segments and locations.

---

## 📂 Dataset

**File:** `website_performance_analytics.csv`
**Records:** 5,870 visitor sessions

| Variable | Description |
|----------|-------------|
| Visitor_ID | Unique identifier for each visitor |
| Page_Views | Number of pages viewed per session |
| Session_Duration | Duration of session in seconds |
| Bounce_Rate | % of visitors leaving after one page |
| Conversion_Rate | % of visitors completing a desired action |
| Traffic_Source | Organic, Direct, Social Media, Referral |
| Exit_Pages | Contact Us, Checkout, Homepage, Blog, Product Page |
| Load_Time | Page load time in seconds |
| Visitor_Type | New or Returning |
| Location | US city of the visitor |

---

## 🛠️ Data Preparation

- Converted `Bounce_Rate` and `Conversion_Rate` from decimals to **percentage format** with zero decimal places
- Assigned **City** data category to the `Location` variable for accurate map plotting

---

## 📊 Dashboard Features

### 🔢 KPI Cards
| Metric | Value |
|--------|-------|
| Average Page Views | 5 |
| Average Session Duration | 300 seconds |
| Average Bounce Rate | 50% |
| Average Conversion Rate | 5% |

### 🍩 Donut Charts
- **Average Bounce Rate by Visitor Type** — New (49.92%) vs Returning (50.08%)
- **Average Conversion Rate by Visitor Type** — New (50.37%) vs Returning (49.63%)

### 📊 Bar Chart
- **Average Conversion Rate by Traffic Source**
  - Direct leads with the highest average conversion rate
  - Followed by Organic, Social Media, and Referral

### 🗺️ Map Chart
- **Average Conversion Rate by Location** — plotted across 20 US cities

### 📋 Table — Top 100 Conversions
- Columns: Visitor_ID, Avg Page Views, Avg Session Duration, Avg Conversion Rate
- Sorted by **Conversion Rate (descending)**
- Filtered to show **Top 100 visitors** by average conversion rate
- Cell elements (data bars) applied to all columns except Visitor_ID

### 🔍 Interactive Filter
- **Exit Pages slicer** in the title bar — filter entire dashboard by: Blog, Checkout, Contact Us, Homepage, Product Page

---

## 🔍 Key Insights

- New visitors make up **60%** of all sessions while returning visitors account for **40%**
- **Direct traffic** generates the highest average conversion rate among all traffic sources
- Bounce rates are almost evenly split between New and Returning visitors (~50% each)
- Conversion rates are consistent across visitor types, suggesting the website performs equally for both segments

---

## 🛠️ Tools Used

- **Power BI Desktop**
  - KPI Cards
  - Donut Charts
  - Clustered Bar Chart
  - Map Visual (Bing Maps)
  - Table with Cell Elements
  - Slicers

---

## 👤 Author

**Destiny Airhiavbere**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](http://www.linkedin.com/in/airhiavbere-destiny-osaruonamen-847741406)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:destinyairhiavbere42@gmail.com)
