# terminal-history

[![](https://img.shields.io/badge/project-link-green)](https://github.com/MiloniAtal/terminal-tracker)
[![](https://img.shields.io/github/license/MiloniAtal/terminal-tracker)](https://github.com/MiloniAtal/terminal-tracker/blob/main/LICENSE)
[![Build Status](https://github.com/MiloniAtal/terminal-tracker/workflows/Build%20Status/badge.svg?branch=main)](https://github.com/MiloniAtal/terminal-tracker/actions?query=workflow%3A%22Build+Status%22)
[![PyPI](https://img.shields.io/pypi/v/terminal-tracker)](https://pypi.org/project/terminal-tracker/)
[![Documentation Status](https://readthedocs.org/projects/terminal-tracker/badge/?version=latest)](https://terminal-tracker.readthedocs.io/en/latest/?badge=latest)

Maintaining a history of terminal commands executed for a folder/project from any terminal.

## Motivation

It often happens that you forget how to setup a project or forget a command that you used as a solution to an error. And, once we close the terminal the history of commands is lost.

## Solution

Build a tool that maintains the history of all the commands executed and the timestamp in a file in the project folder itself. The tool can be customised to take in preferences like storing only new commands or deleting older that 10 days of commands. The tool can also provide efficient searching and segregration of the commands, for example segregating all the software installs.
