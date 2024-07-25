News Scraper

This Python script scrapes business news articles from the Indian Express website and saves the extracted data into a CSV file.

Requirements

I have used anaconda notebook which had the requests and BeautifulSoup libraries.

if your using Python 3.x

Required Python packages:
requests
BeautifulSoup

Install the required packages using pip:
Copy code
pip install requests beautifulsoup4

Usage
Clone the repository to your local machine:
Copy code
git clone https://github.com/your-username/news-scraper.git
cd news-scraper

Run the script:
bash
Copy code
python news_scraper.py

Output:
The script will scrape business news articles from the Indian Express website and save the data into a CSV file named business_news.csv.
Script Explanation
news_scraper.py: Python script that fetches business news articles from the specified URL using requests and parses HTML content with BeautifulSoup.
The script simulates a browser request using custom headers to fetch the webpage content.
It searches for the  element with class nation to locate the section containing business news articles.
For each article found  with class articles, it extracts the title  with class title and publication date  with class date.
Extracted data is stored in a CSV file business_news.csv with columns Title of article and Date.

Contributions are welcome! Feel free to fork the repository, create pull requests, or open issues for any suggestions or improvements.
