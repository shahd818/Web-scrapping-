🕸️ Web Scraping Project using Python & BeautifulSoup

📌 Overview

This project is a Python-based web scraper built with BeautifulSoup. It scrapes book data (like title, price, availability, and rating) from the website Books to Scrape and saves the extracted information into a CSV file.

🧰 Tools & Technologies
Python 3.x

BeautifulSoup (bs4) – for parsing HTML

Requests – to fetch webpage content

pandas – to structure and export data as CSV

Visual Studio Code (VS Code) – as the development environment

📂 Project Structure
bash
Copy
Edit
Web-scrapping-/
├── Book-details-scraped.csv     # Output file containing the scraped data
├── Books_to_scrape.py           # Python script for scraping
└── README.md                    # Project documentation
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/shahd818/Web-scrapping-.git
cd Web-scrapping-
2. Install Dependencies
In your VS Code terminal, run:
pip install beautifulsoup4 requests pandas
3. Run the Script
In the terminal inside VS Code:
python Books_to_scrape.py
The script will run and generate a file named Book-details-scraped.csv with the extracted data.

📝 Features
Scrapes book information from all pages on the site.

Handles pagination automatically.

Saves results in a structured CSV format.

Easy to extend for other sites.

⚠️ Disclaimer
This project is for educational purposes only. Please respect the website's robots.txt file and terms of service. Do not scrape data without permission.

👩‍💻 Author
Shahad Albolwi
GitHub: shahd818
[LinkedIn](https://www.linkedin.com/in/shahad-hassan-562451297?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) | shahadalbolwi@gmail.com
