# USAU Scraper

[![Build Status](https://github.com/erin2722/usau-scraper/workflows/Build%20Status/badge.svg?branch=main)](https://github.com/ColumbiaOSS/example-project-python/actions?query=workflow%3A%22Build+Status%22)
![Apache Liscence](https://img.shields.io/github/license/erin2722/usau-scraper?color=f72d2d)
[![PyPI](https://img.shields.io/pypi/v/usau-scraper?color=2d2df7)](https://pypi.org/project/usau-scraper/)
[![Docs](https://img.shields.io/badge/documentation-gh%20pages-%23fffb03)](https://erin2722.github.io/usau-scraper/)

## Description

The USAU scraper is a data collector that allows developers to easily aggregate and use team results, rosters, and schedule data from the [USAU website](https://play.usaultimate.org/events/tournament/?ViewAll=false&IsLeagueType=false&IsClinic=false&FilterByCategory=AE).
USAU (USA Ultimate) is the governing body of ultimate frisbee, and its website (which is notoriously hard to navigate) contains all of the information
about high school, college, and club ultimate frisbee teams. Right now, there is no easy way to access this data, and so I think that building a data
scraper that would allow other developers to easily use the data on the USAU site would open the door to more data analytics and other projects concerning
ultimate frisbee.

## Repository Link

<https://github.com/erin2722/usau-scraper>

## Features (MVP)

- A function that, given a team name and a season, returns their schedule and record.
- A function that, given a team name and a season, returns its roster.
- A function that, given a tournament name, returns the results of the tournament.

## Additional features

- A function that, given a college division, returns the current standings of that division.
- An additional plugin to [ultimate frisbee rankings](http://www.frisbee-rankings.com/) that shows how team ranking has changed over time.
- An additional plugin to [ultiworld](https://ultiworld.com/) to show recent articles given a team name or college division.
- More features tbd!
