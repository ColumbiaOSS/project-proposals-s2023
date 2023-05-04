# pro-football-reference-web-scraper

[![](https://img.shields.io/badge/project-link-green)](https://github.com/mjk2244/pro-football-reference-web-scraper) [![License](https://img.shields.io/github/license/mjk2244/pro-football-reference-web-scraper)](https://opensource.org/licenses/Apache-2.0) [![Package Status](https://img.shields.io/github/actions/workflow/status/mjk2244/pro-football-reference-web-scraper/build.yml)](https://github.com/mjk2244/pro-football-reference-web-scraper/) [![PyPI](https://img.shields.io/pypi/v/pro-football-reference-web-scraper)](https://pypi.org/project/pro-football-reference-web-scraper/)
[![readthedocs](https://img.shields.io/readthedocs/pro-football-reference-web-scraper)](https://pro-football-reference-web-scraper.readthedocs.io/en/latest/) [![Github Pages Docs](https://img.shields.io/badge/docs-gh--pages-blue)](https://mjk2244.github.io/pro-football-reference-web-scraper/)

## Description

[Pro Football Reference](https://www.pro-football-reference.com/) provides tons of useful NFL data, from team rosters to historic draft records to individual player game logs. With the recent rise in interest in fantasy sports and sports betting, sites like PFR are incredibly valuable both for casual fans and for more serious, analytics-oriented sports gamers who want to get an edge in their fantasy leagues or gambling endeavours.  

PFR is also abundantly useful for people who make social media content related to fantasy sports and sports betting. For example, with the Super Bowl coming up, someone may want to make a graphic commemorating the 5 best fantasy football performances in Super Bowl history (a situation I found myself in last year). Without an appropriate web scraper, such a project would take hours of manual labor transferring the relevant stats to a spreadsheet.

I would like to build a PFR web scraper library that allows users to easily retrieve team- and player-specific data, both for fantasy and non-fantasy purposes. Some potential features include:

- Given a player and a season, return their stats
- Given a player and an integer x, return their stats over the last x games
- Given a team and a season, return the results of all of their games
- Given a player, a season, and a fantasy format (standard, half-PPR, PPR), return their stats for each game, including total fantasy points
- Given a team and a season, return the team's roster from that season
- Given a team, a season, and an integer x, return that team's top x fantasy performances from that season
