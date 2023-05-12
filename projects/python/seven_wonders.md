# 7Wonder-RL-Lib

## Description

[Github Repo](https://github.com/MirrorCraze/7Wonder-RL-Lib)

[![codecov](https://codecov.io/gh/MirrorCraze/7Wonder-RL-Lib/branch/main/graph/badge.svg?token=7JDHEZ4E76)](https://codecov.io/gh/MirrorCraze/7Wonder-RL-Lib)
[![CodeQL](https://github.com/MirrorCraze/7Wonder-RL-Lib/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/MirrorCraze/7Wonder-RL-Lib/actions/workflows/github-code-scanning/codeql)
[![Build + CodeCov + Pylint/Black](https://github.com/MirrorCraze/7Wonder-RL-Lib/actions/workflows/build.yml/badge.svg)](https://github.com/MirrorCraze/7Wonder-RL-Lib/actions/workflows/build.yml)
[![PyPI](https://img.shields.io/pypi/v/7Wonder-RL-Lib)](https://pypi.org/project/7Wonder-RL-Lib/0.1.0/)
[![GitHub Pages](https://img.shields.io/badge/Github%20Pages-Link-lightgrey)](https://mirrorcraze.github.io/7Wonder-RL-Lib/)

There are multiple environments for the AI game testing. However, environments implemented now are mostly covered only the traditional board games (Go, Chess, etc.) or 52-card based card games (Poker, Rummy, etc.) where games do not really have interactions with other players.

Most of the Euro-games board games are good game environments to test the algorithm on as there are many aspects to explore, such as tradings, dealing with imperfect informations, stochastic elements, etc.

7 Wonders board games introduced multiple elements mentioned above which are good for testing out new algorithm. This library will cover basic game systems and allow users to customize the environments with custom state space and rewarding systems.
