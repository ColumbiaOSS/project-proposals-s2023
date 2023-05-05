# CB_IPO

Name: Leon Wu

[![Build Status](https://github.com/llw2128/CB_IPO/workflows/Build%20Status/badge.svg?branch=main)](https://github.com/llw2128/CB_IPO/actions?query=workflow%3A%22Build+Status%22)
[![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![PyPI](https://img.shields.io/pypi/v/CB_IPO)](https://pypi.org/project/CB-IPO/)
[![Documentation](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white)](https://llw2128.github.io/CB_IPO/)

## Description

Researching information on trends for companies can be incredibly tedious, this library will automate part of the proccess making DCF building and IPO research easier. CB_IPO is a library that will fetch information on recent and historical IPOs by scraping the SEC EDGAR database for S-1 filings. These queries can also be modified to search for certain dates, and additional forms. This data can subsequently be placed in a pandas dataframe for the sake of easy viewing.

A second proccess this autmoates is finding the specific 10-K filings for a company. By inputing a cik, a list of 10-k filing links will be returned. With these links, the library also has a function for using a 10-k link and returning a dictionary or dataframe of info such as assets, liabilities, and income. In addition it can calculate financial raitos and return them as a dataframe.

The project will be written in python and use selenium to run a local webscraper.

[CB_IPO](https://github.com/llw2128/CB_IPO)
