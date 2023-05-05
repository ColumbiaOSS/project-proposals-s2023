# SEC Web Scraper

[![](https://shields.io/badge/project-link-green)](https://github.com/deji725/sec-web-scraper)
![Github](https://github.com/deji725/sec-web-scraper/actions/workflows/makefile.yml/badge.svg)
![Github](https://img.shields.io/github/license/deji725/sec-web-scraper)
[![docs](https://img.shields.io/github/actions/workflow/status/deji725/sec-web-scraper/docs.yml?label=docs)](https://deji725.github.io/sec-web-scraper/)
[![PyPI](https://img.shields.io/pypi/v/sec-web-scraper)](https://pypi.org/project/sec-web-scraper/)

## Description

`sec-web-scraper` will be a library for scraping certain financial documents from the EDGAR database such as the 10-K (and it's versions such as 10-K405,10-KSB), 20-F and 40-F.

The two main features of the library will be:

- A document downloader portion that will fetch documents from the EDGAR database based on parameters such as a text query, time period, company ticker, and file type.
- A scraper that will parse sections and information from the retrieved files. There are many different file types with different sections so this portion will focus on the 20-F and 40-F. If there is more time, then more file types can be accomodated.
  - One example of information parsed from these files is the Operating and Financial Review (Item 5) portion. This section contains key decision made by a company's management in mitigating issues that are affecting the company's current financial condition.
