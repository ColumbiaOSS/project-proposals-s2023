# pynrm

![Build Status](https://github.com/katehyerinjeon/pynrm/actions/workflows/build.yml/badge.svg)
![License](https://img.shields.io/github/license/katehyerinjeon/pynrm)
![PyPI](https://img.shields.io/pypi/v/pynrm)
[![Docs](https://img.shields.io/readthedocs/pynrm.svg)](https://pynrm.readthedocs.io/)

`pynrm` is a lightweight and extensible Python library for livestock breeding simulation. Link to repository can be found [here](https://github.com/katehyerinjeon/pynrm).

## Overview

The numerator relationship matrix describes additive genetic relationships within a population.
Numerous evaluation-selection systems have been devised to produce populations with favorable genetic responses while maintaining moderate to low rates of inbreeding.
`pynrm` provides a simple yet powerful simulation tool to forecast the stochastic impacts of these systems.
One major bottleneck to running these simulations is that as the number of animals bred increases, the size of the matrix grows exponentially.
`pynrm` efficiently solves for the numerator relationship matrix values by tracing up the pedigree for only the relevant ancestors, thereby minimizing computational overhead.
