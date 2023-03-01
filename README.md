# Instagram Scraper using Selenium with Python

This is a simple Instagram scraper built using Selenium with Python. This scraper can be used to extract data from
public Instagram profiles such as followers, following, posts, and post information such as likes and comments.

## Requirements:

- Python 3.x
- Selenium
- ChromeDriver

## Installation

- Install Python 3.x from the official website.
- Install Selenium using pip: pip install selenium
- Download ChromeDriver from the official website: https://sites.google.com/a/chromium.org/chromedriver/downloads

## Usage

1. Open .env.example file in your code editor.
2. Replace variables with your own settings.
3. Rename .env.example to .env file.
4. Install dependencies `pip install -r requirements.txt`
5. Run `main.py`

The script will open a new Chrome window, log in to your Instagram account, and scrape the target profile's data. The
data will be saved in a JSON file named instagram_data.json.

## Limitations

This scraper can only be used to extract data from public Instagram profiles.
Instagram limits the number of requests per hour, so the script may stop working if you exceed this limit.
