# Bitcoin Market Analysis and News Integration

## Overview
This project focuses on collecting, integrating, and analyzing data from multiple sources to explore the Bitcoin market and related news. The project fulfills academic requirements for data collection, integration, quality assessment, and exploratory analysis.  

Two data sources were chosen:  
1. **Bitcoin market data** from Binance API  
2. **News articles** related to Bitcoin from The New York Times API  

The datasets are integrated, enriched, stored in a database, and analyzed to provide insights about market trends and news sentiment.

---

## Project Requirements

- **Approval:** The project must be approved by the teacher.  
- **Team:** 1–3 students per project.  
- **Data Sources:** At least two different sources collected using:
  - API (used for both Binance and NYTimes)  
  - Web scraping  
  - Download dataset/query (if API or scraping is insufficient)  
- **Data Integration:** Datasets are merged and enriched.  
- **Storage:** Data stored in a SQL or NoSQL database.  
- **Exploratory Data Analysis (EDA):** Performed on individual and integrated datasets.  
- **Data Quality:** Assessment and improvement applied on at least two quality dimensions.  
- **Project Revision:** If the project is insufficient or the grade is refused, a new project must be presented.

---

## Data Sources

### 1. Binance API
- **Type:** Cryptocurrency market data  
- **Data Collected:** Prices, volumes, trading pairs, timestamps  
- **Purpose:** Analyze market trends and volatility of Bitcoin.

### 2. The New York Times API
- **Type:** News articles  
- **Data Collected:** Article titles, publication date, URL, content  
- **Purpose:** Explore sentiment and news coverage trends related to Bitcoin.

---

## Data Storage

- **Database Type:** [Specify SQL or NoSQL, e.g., PostgreSQL / MongoDB]  
- **Structure:**
  - Bitcoin market data table/collection  
  - News articles table/collection  
  - Integrated dataset linking market trends with news events

---

## Data Processing

- **Integration:** Merge datasets based on timestamps and relevant events.  
- **Enrichment:** Add features like sentiment scores for news articles.  
- **Quality Assessment:**  
  - **Completeness:** Handling missing data  
  - **Consistency:** Format and type standardization

---

## Exploratory Data Analysis (EDA)

- **Bitcoin Market Analysis:** Trend visualization, volume analysis, volatility metrics.  
- **News Analysis:** Sentiment distribution, frequency over time, correlation with market trends.  
- **Integrated Analysis:** Insights from combining market and news data (e.g., price reaction to major news events).

---

## Project Usage

1. Clone the repository:  
```bash
git clone https://github.com/aronetommaso/DataMan-Project.git
