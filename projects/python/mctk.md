# Model Checking Toolkit

[![](https://img.shields.io/badge/project-link-green)](https://github.com/marcusm117/mctk/tree/dev) [![PyPI](https://img.shields.io/pypi/v/mctk-py?color=blue&label=PyPI)](https://pypi.org/project/mctk-py/) [![CI](https://github.com/marcusm117/mctk/workflows/CI/badge.svg?branch=dev)](https://github.com/marcusm117/mctk/actions?query=workflow%3A%22Build+Status%22) [![codecov](https://codecov.io/gh/marcusm117/mctk/branch/dev/graph/badge.svg)](https://codecov.io/gh/marcusm117/mctk) [![License](https://img.shields.io/badge/License-Apache_2.0-green)](https://github.com/marcusm117/mctk/blob/dev/LICENSE) [![Issues](https://img.shields.io/github/issues/marcusm117/FV_mctk?color=red&label=Issues)](https://github.com/marcusm117/mctk/issues)

## Description

`mctk` is a Python library for Explicit-State Model Checking (will also support Symbolic Model Checking and Bounded Model Checking in the future) on Kripke Structures (will also support other Transition Systems) supporting the CTL(Computation Tree Logic) operators: **EX, EU, EG, EF, AX, AU, AG, AF**, and the Propositional Logic operators: **NOT, AND, OR, IMPLIES, IFF**.

Users can use functions that implements CTL operators to formally verify if a Kripke Structure (can be created during runtime or input in a JSON file) satisfies certain CTL properties. All checking functions will return a set of states that satisfy the CTL property, which means that if any start state of the Kripke Structure is in the returned set, then the Kripke Structure satisfies the CTL property.
