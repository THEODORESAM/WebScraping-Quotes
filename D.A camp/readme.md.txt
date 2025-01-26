# Web Scraping Quotes from a Website

This repository contains a Python script that scrapes quotes and their corresponding authors from the website [Quotes to Scrape](https://quotes.toscrape.com/). The script extracts data from the first 10 pages of the website and saves the results in an Excel file.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The script uses web scraping techniques to extract quotes and their authors from the [Quotes to Scrape](https://quotes.toscrape.com/) website. It navigates through the first 10 pages of the website, collects the data, and stores it in a structured format (Excel file) for further analysis or use.

## Features

- **Web Scraping**: Extracts quotes and authors from the website.
- **Pagination Handling**: Automatically navigates through multiple pages (up to 10 pages).
- **Data Storage**: Saves the scraped data in an Excel file (`quotes.xlsx`).
- **User-Friendly**: Easy-to-understand code with comments for better readability.

## Requirements

To run this script, you need the following Python libraries installed:

- `requests`: To send HTTP requests to the website.
- `beautifulsoup4`: To parse the HTML content of the website.
- `pandas`: To store the scraped data in an Excel file.
- `lxml`: To improve the parsing speed of BeautifulSoup.

You can install these libraries using pip:

```bash
pip install requests beautifulsoup4 pandas lxml