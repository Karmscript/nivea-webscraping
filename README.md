🧴 Nivea Skincare Product Web Scraper & Ingredient Grouping
Overview
This project scrapes product information from Nivea’s official Jumia store, extracts product attributes, and automatically groups products with similar ingredient compositions.

Main objectives:

Extract detailed product data:

Name, brand, description

Price, SKU, size/volume

Product line, skin concern

Image URL, product URL

Ingredients list

Group products sharing two or more ingredients.

Provide data visualizations for insights.

Tools & Libraries
Python – Core programming language

BeautifulSoup – HTML parsing & web scraping

Requests – HTTP requests

Pandas – Data manipulation & CSV export

Matplotlib – Data visualization

Key Outputs
nivea_products.csv → Complete scraped dataset

nivea_grouped_products.csv → Grouped dataset based on ingredient similarity

Interactive plots showing ingredient frequency and grouping insights

Visuals
Sample Ingredient Frequency Plot	Grouped Products Distribution
(insert screenshot)	(insert screenshot)

How to Run
bash
Copy
Edit
# Clone repo
git clone https://github.com/YOUR-USERNAME/nivea-webscraper.git
cd nivea-webscraper

# Install dependencies
pip install -r requirements.txt

# Run script
python scrape_nivea.py
Applications
Market analysis for skincare products

Competitive ingredient comparison

E-commerce product grouping for recommendation systems

Author
Ramadan Ahmed
📧ahmedramadanbamidele@gmail.com
🔗 www.linkedin.com/in/ramadan-ahmed-797846219

