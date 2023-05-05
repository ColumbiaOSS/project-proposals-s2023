# pyobjectify

[Repo link](https://github.com/wu-rymd/pyobjectify)

## pyobjectify [![PyPI](https://img.shields.io/pypi/v/pyobjectify?style=flat-square&color=222222)](https://pypi.org/project/pyobjectify) [![docs](https://img.shields.io/badge/-docs-black?style=flat-square)](https://wu-rymd.github.io/pyobjectify/docs/_build/html/index.html)

Bridge the gap across the different file formats and streamline the process to accessing ingested data via Python objects

![license](https://img.shields.io/badge/license-MIT-green?style=flat-square&color=022169) ![issues](https://img.shields.io/github/issues/wu-rymd/pyobjectify?style=flat-square&color=841C1C) [![codecov](https://codecov.io/gh/wu-rymd/pyobjectify/branch/main/graph/badge.svg?token=410L0PN9UC)](https://codecov.io/gh/wu-rymd/pyobjectify) ![build](https://img.shields.io/github/actions/workflow/status/wu-rymd/pyobjectify/build.yml?style=flat-square)

## Overview

Open data is abound. For example, NYC Open Data has over 3,000 datasets spanning over 97 agencies in New York City. This data comes in many different formats, including CSV, JSON, XML, XLS/XLSX, KML, KMZ, Shapefile, GeoJSON, JSON, and more.

In order to import and analyze the data in Python involves sending a request to download the raw data, then converting it into a Python object so that methods can be used to parse its contents. However, this process varies across the many different data types.

This project aims to streamline this process and bridge the gap across the different file formats to allow the end user to get started on data analytics more quickly with a quick function call.

## Install from pip

```bash
pip install pyobjectify
```

## Quick start

```python
import pyobjectify
import pandas as pd

json_dict = pyobjectify.from_url("https://bit.ly/42KCUSv")  # URL holds JSON data, returns data in dict
json_df = pyobjectify.from_url("https://bit.ly/42KCUSv", pd.DataFrame)  # User-specified output data type
```

## Supported types

### Connectivity types

- Local files (_e.g._ `./relative/example.json`, `/absolute/path/example.json`)
- Online, static (_e.g._ `https://some.website/example.json`, `http://bit.ly/some-json-endpoint`)

For example, at the moment, a data stream from the Internet is not supported.

#### Resource (input) data types

- JSON
- CSV
- TSV
- XML
- XLSX

#### Supported conversions

- JSON &rarr; `dict`, `list`, `pandas.DataFrame`
- CSV &rarr; `list`
- TSV &rarr; `list`
- XML &rarr; `dict`
- XLSX &rarr; `dict`
