# 🇮🇳 India Sports Rankings Scraper

This Python script scrapes national sports rankings data from **FanRank.org**, parses it into a structured format, and exports the data as CSV, Excel, and JSON files for easy analysis or reporting.

---

##  Overview

The script loops through multiple pages of the [FanRank India Rankings](https://www.fanrank.org/ranking/india-sports-rankings-1) website (pages 1–18), scrapes tabular data containing sport, format, gender, and rank, and compiles it into structured datasets. The results are saved in three formats: `.csv`, `.xlsx`, and `.json`.

---

##  Source

- Website: [https://www.fanrank.org](https://www.fanrank.org)
- Start URL: [https://www.fanrank.org/ranking/india-sports-rankings-1](https://www.fanrank.org/ranking/india-sports-rankings-1)

---

##  Libraries Used

| Library          | Purpose                                 |
|------------------|-----------------------------------------|
| `requests`       | To send HTTP GET requests               |
| `beautifulsoup4` | To parse and extract HTML content       |
| `pandas`         | To create and export dataframes         |
| `json`           | To export data in JSON format           |

---

##  Repository Structure

india-sports-rankings/

├── script.py                      # Main scraper script

├── india_sports_rankings.csv      # Output CSV file

├── india_sports_rankings.xlsx     # Output Excel file

└── india_sports_rankings.json     # Output JSON file

---

## How To run
Clone the repository or download the script:

   **git clone https://github.com/your-username/india-sports-rankings.git**
   
   **cd india-sports-rankings**

Install the required libraries:

  **pip install requests beautifulsoup4 pandas**

Run the script:

  **python script.py**

View the output files:

-india_sports_rankings.csv – Viewable in any spreadsheet tool.

-india_sports_rankings.xlsx – Excel-friendly version.

-india_sports_rankings.json – Machine-readable format.
