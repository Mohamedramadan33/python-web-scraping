# Web Scraping Task

This project scrapes data from a given HTML page and saves it into CSV and JSON files.

## Files Created
- Extract_Text_Data.csv (headings + paragraphs)
- Extract_Table_Data.csv (product, price, inStock)
- Product_Information.json (book/product cards)
- Form_Details.json (form fields)
- Links_Multimedia.json (video link)
- Featured_Products.json (featured products)

## How to Run
1. Install Python 3.
2. Install libraries:
   ```
   pip install requests beautifulsoup4
   ```
3. Run the script:
   ```
   python scrape.py
   ```

## Tools
Python, requests, BeautifulSoup, csv, json

## Notes
Used `utf-8-sig` to fix special characters in Excel.

