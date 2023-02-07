# valparse

[![](https://img.shields.io/badge/valparse-link-green)](https://github.com/tzussman/valparse)

## Description
`valparse` is a library for parsing `valgrind` XML output. In contrast to other
`valgrind` output parsing library, `valparse` uses the XML file option provided
by `valgrind` in order to robustly parse the output in a structured matter,
rather than relying on brittle regexes parsing the `valgrind` text output.
 
This allows users to correctly handle fatal signals, along with programatically
generating `valgrind` suppression files.
