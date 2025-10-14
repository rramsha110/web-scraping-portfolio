# 🚗 CarWale New Cars Scraper

This project scrapes data about **car brands, models, prices, and links** from [CarWale - New Cars](https://www.carwale.com/new-cars/).
The scraped data is saved into CSV files for easy analysis.

## 📂 Project Structure

* `carwale_scraper.ipynb` → Jupyter Notebook with the full scraping logic
* `carwale_brands.csv` → Extracted car brands with links
* `carwale_new_cars.csv` → Extracted car models, prices, and links
* `Carwaale_Newcars.html` → Raw saved HTML page from CarWale (kept for reference & offline testing)

## 🛠 Tools & Libraries

* **Python 3**
* **BeautifulSoup4** → HTML parsing
* **Requests** → Fetching webpage content
* **Regular Expressions (re)** → Extracting prices and details
* **CSV module** → Saving structured data

## ▶️ How to Run

1. Clone this repository (or just this folder if part of a bigger portfolio):

   ```bash
   git clone https://github.com/rramsha110/web-scraping-portfolio.git
   cd web-scraping-portfolio/CarWale_Scraper
   ```

2. Install dependencies:

   ```bash
   pip install requests beautifulsoup4
   ```

3. Open the Jupyter Notebook and run all cells:

   ```bash
   jupyter notebook carwale_scraper.ipynb
   ```

4. Output files (`carwale_brands.csv`, `carwale_new_cars.csv`) will be generated in the same folder.

## 📊 Sample Output

**carwale_brands.csv**

| Brand         | Link                                                                                     |
| ------------- | ---------------------------------------------------------------------------------------- |
| Maruti Suzuki | [https://www.carwale.com/marutisuzuki-cars/](https://www.carwale.com/marutisuzuki-cars/) |
| Hyundai       | [https://www.carwale.com/hyundai-cars/](https://www.carwale.com/hyundai-cars/)           |

**carwale_new_cars.csv**

| Model         | Price     | Link                                                                                                   |
| ------------- | --------- | ------------------------------------------------------------------------------------------------------ |
| Maruti Swift  | ₹6.5 Lakh | [https://www.carwale.com/maruti-suzuki-cars/swift/](https://www.carwale.com/maruti-suzuki-cars/swift/) |
| Hyundai Creta | ₹11 Lakh  | [https://www.carwale.com/hyundai-cars/creta/](https://www.carwale.com/hyundai-cars/creta/)             |

---

## 📌 Notes

* This scraper is for **educational purposes only**.
* Website structures may change, so scraping logic might need updates.

Would you like me to also make a **main README.md** for your entire `web-scraping-portfolio` repo (like an index linking CarWale, Jobs, API scrapers), so everything stays nicely organized?
