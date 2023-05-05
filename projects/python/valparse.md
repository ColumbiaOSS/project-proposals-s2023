# valparse

[![](https://img.shields.io/badge/valparse-link-green)](https://github.com/tzussman/valparse)
[![Build Status](https://github.com/tzussman/valparse/workflows/Build%20Status/badge.svg?branch=main)](https://github.com/tzussman/valparse/actions?query=workflow%3A%22Build+Status%22)
[![License](https://img.shields.io/github/license/tzussman/valparse)](https://github.com/tzussman/valparse)
[![PyPI](https://img.shields.io/pypi/v/valparse)](https://pypi.org/project/valparse/)
[![Docs](https://img.shields.io/badge/-docs-blueviolet)](https://tzussman.github.io/valparse)

## Description

`valparse` is a library for parsing `valgrind` XML output. In contrast to other
`valgrind` output parsing library, `valparse` uses the XML file option provided
by `valgrind` in order to robustly parse the output in a structured matter,
rather than relying on brittle regexes parsing the `valgrind` text output.

This allows users to correctly handle fatal signals, along with programatically
generating `valgrind` suppression files.
