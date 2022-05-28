# Desktop-Application
Amazon Scraper using Selectorlib
A simple amazon scraper to extract product details and prices from Amazon.com using Python Requests and Selectorlib.

Full article at ScrapeHero Tutorials

There are two simple scrapers in this project.

Amazon Product Page Scraper amazon.py
Amazon Search Results Page Scraper searchresults.py
Note: A completely web browser based commercial version of these scrapers are available in ScrapeHero Marketplace

Usage
From a terminal

Activate the Virtual Environment source .venv/bin/activate (Optional)
Install Requirements pip3 install -r requirements.txt
Scrape Product Details from Product Page
Add Amazon Product URLS to urls.txt
Run python3 amazon.py
Get data from output.jsonl
Scrape Products from Search Results
This scraper only scrapes product from the first page of search results

Add Amazon Product URLS to search_results_urls.txt
Run python3 searchresults.py
Get data from search_results_output.jsonl
