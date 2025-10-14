🚗 CarWale New Cars Scraper

This project scrapes data from [CarWale - New Cars](https://www.carwale.com/new-cars/).  
It extracts **car brands, models, prices, and links** from the CarWale website and saves the results into CSV files.

📂 Files in this Project
- `Carwaale_Newcars.html` → raw saved HTML page
- `carwale_brands.csv` → extracted car brands with links
- `carwale_new_cars.csv` → extracted car models, prices, and links
- `carwale_scraper.ipynb` → Python Jupyter Notebook with full scraping code

🛠️ Tools Used
- Python  
- BeautifulSoup (HTML parsing)  
- Regular Expressions (price extraction)  
- CSV module (saving structured data)  

🚀 How to Run
1. Clone this repo:
   ```bash
git clone https://github.com/rramsha110/web-scraping-portfolio.git
cd web-scraping-portfolio
pip install beautifulsoup4 requests
jupyter notebook carwaale_scraper.ipynb
Run all cells to scrape and generate CSV files.

   
