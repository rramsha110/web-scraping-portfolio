
* **`raw_html_jobs/page1.html`** → Raw saved HTML (reference copy of the scraped page)
* **`job_scraper.ipynb`** → Notebook with scraping + extraction logic
* **`jobs_all_pages.csv`** → Clean tabular output
* **`jobs_all_pages.json`** → Structured JSON output
* 
# 💼 Jobs Scraper (Fake Jobs Portal)

This project scrapes job postings from the [Fake Jobs Portal](https://realpython.github.io/fake-jobs/).  
It saves raw HTML pages for offline use, extracts **job title, company, location, and link**,  
and stores the results into both **CSV** and **JSON** formats.



## 📂 Files in this Project
- `raw_html_jobs/page1.html` → Example of a saved raw job listing page  
- `job_scraper.ipynb` → Jupyter Notebook with full scraping + parsing logic  
- `jobs_all_pages.csv` → Extracted job postings in CSV format  
- `jobs_all_pages.json` → Extracted job postings in JSON format  

---

## 🛠 Tools Used
- Python  
- `requests` → Fetching job pages  
- `BeautifulSoup` → Parsing job details  
- `csv` & `json` → Data storage  
- `os`, `time` → File handling & polite scraping  


## 🚀 Features
- Handles **pagination** (scrapes multiple pages automatically)  
- Saves raw HTML files for **offline analysis**  
- Extracts **title, company, location, and link** of each job  
- Exports data into **CSV + JSON** for flexibility  


## ▶️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/rramsha110/web-scraping-portfolio.git
   cd web-scraping-portfolio/Jobs_Scraper
````

2. Install dependencies:

   ```bash
   pip install requests beautifulsoup4
   ```
3. Open in Jupyter Notebook:

   ```bash
   jupyter notebook job_scraper.ipynb
   ```

   Or run as a script (if converted to `.py`):

   ```bash
   python job_scraper.py
   ```


## 📊 Sample Output

**CSV Example:**

| Title            | Company      | Location     | Link        |
| ---------------- | ------------ | ------------ | ----------- |
| Python Developer | Example Corp | Remote       | https://... |
| Data Analyst     | Data Inc.    | New York, US | https://... |


✅ This scraper demonstrates **offline storage + parsing + structured export**.
