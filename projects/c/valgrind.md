# Valgrind

[![](https://img.shields.io/badge/Valgrind-docs-green)](https://valgrind.org/)
[![](https://img.shields.io/badge/Valgrind-repo-blue)](https://sourceware.org/git/?p=valgrind.git;a=tree)

Valgrind is a dynamic binary instrumentation tool, which is frequently used to catch memory leaks and errors.
Valgrind is able to track programs across `fork()`s, along with producing XML output files containing the
results of running it.


## Issues

- Valgrind incorrectly formats XML output files for child processes - it is missing the starting tags
  for the XML file, leading to incorrect/broken parsing.