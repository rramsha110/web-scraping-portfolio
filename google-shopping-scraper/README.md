# Google Shopping Scraper (SerpApi)

This project demonstrates how to scrape product data from **Google Shopping** using the [SerpApi](https://serpapi.com/) API.  
It extracts product details such as **title, price, store/source, and direct link** and saves them into CSV files for analysis.

## 📌 Features
- Fetches Google Shopping results for a given search term.
- Supports multiple pages of results using SerpApi pagination.
- Cleans and stores product data (no duplicate links).
- Saves output to CSV files (with UTF-8 encoding for ₹ symbol).
- Example product search: *Nothing 45W Charger*.

## 📂 Files Included
- `googleshopping_scraper.ipynb` → Jupyter Notebook with the full scraping logic (pagination + clean results).
- `google_shopping_results.csv` → Output CSV with multiple pages of product results.
- `shopping_results.csv` → Simple one-page scraper output.
- `README.md` → Project explanation and instructions.

## ⚙️ How It Works
1. The script connects to Google Shopping using SerpApi.
2. Extracts:
   - **Title** → Name of the product.  
   - **Price (INR)** → Price displayed on Google Shopping.  
   - **Source** → Seller/store name (e.g., Flipkart, Amazon, Vijay Sales).  
   - **Link** → Direct product page (preferred over Google redirect).  
3. Results are saved in structured CSV format.

## 📊 Example Output (CSV)
| Title                                | Price (INR) | Source         | Link   |
|--------------------------------------|-------------|----------------|--------|
| Nothing 45W Power Adapter            | ₹1,999      | Vijay Sales    | https://... |
| Tart Original 45W Charger Adapter    | ₹599        | JioMart        | https://... |
| Nothing 45W USB-C Power Charger      | ₹1,343.16   | ChargingCable  | https://... |


## 🚀 Usage
1. Replace `Your_api_key` in the code with your own SerpApi API key.
2. Run the script in Jupyter Notebook or Python.
3. The extracted data will be saved into `google_shopping_results.csv`.

## 📝 Notes
- This project is for **learning and portfolio purposes only**.
- Google Shopping is accessed through **SerpApi**, which handles the scraping and returns clean structured JSON.
- To avoid showing your API key publicly, keep it in a separate config file or use environment variables.

