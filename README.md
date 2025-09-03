%%writefile README.md
# Python.org Job Scraper

This project is a simple Python script that scrapes job listings from [python.org/jobs](https://www.python.org/jobs/) and saves them into a CSV file.  
It navigates through all job listing pages, extracts job details, and compiles them into a structured dataset for analysis.

---

## Features
- Scrapes **all pages** of job listings on python.org
- Extracts:
  - Job Title
  - Company
  - Location
  - Job Type
  - Date Posted
  - Category
- Saves results to a clean, downloadable CSV file
- Designed for use in **Google Colab** or locally

---

## Requirements
Install the following Python libraries before running the script:

```bash
pip install beautifulsoup4 requests pandas
