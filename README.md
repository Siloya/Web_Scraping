# AI Web Scraper

## Description

**AI Web Scraper** is a lightweight, AI-assisted web scraping tool built with Python and Streamlit. It allows you to extract website content, clean it, and parse it using natural language instructions. The tool supports dynamic pages and CAPTCHA handling using a remote Selenium WebDriver.

## Tech Stack

- **Python 3.8+**
- **Streamlit** – frontend interface  
- **Selenium** – browser automation  
- **BeautifulSoup** – HTML parsing
- **LangChain** – prompt management  
- **Ollama LLM** – content understanding  
- **python-dotenv** – environment configuration
## Features

-  Web scraping using Selenium with remote browser support  
-  Clean and extract meaningful text from raw HTML  
-  AI-powered content parsing using LLM (Ollama)  
-  Simple and interactive UI with Streamlit


## Quick Setup

```bash
git clone https://github.com/Siloya/Web_Scraping.git
cd Web_Scraping
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
Create a .env file with:
```bash
SBR_WEBDRIVER="http://your_selenium_remote_address:port"
```
## How to Run
```bash
streamlit run app.py
```
- Enter a URL to scrape.
- Describe what you want to extract.
- Click to parse and view the results.
## Environment Setup
Selenium Browser Remote (SBR): Make sure you have a running Selenium server (locally or through a cloud-based service) with the appropriate WebDriver properly configured.
