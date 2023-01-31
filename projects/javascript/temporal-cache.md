
# temporal-cache

[![](https://img.shields.io/badge/project-link-green)](https://github.com/timkpaine/temporal-cache-js)

## Description
`temporal-cache` is a library for caching function calls. However, in contrast with many other caching libraries, it evicts entries in the cache not based on capacity, but based on clock time or time since last call. It has two main features:

- expire a cache entry on a particular second/minute/hour/day/week/month
- expire a cache entry after `N` time since the last call, where `N` is defineable in terms of seconds/minutes/hours/days/weeks/months




