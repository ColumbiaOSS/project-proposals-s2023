# ZKPy

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
![example workflow](https://github.com/sahilmahendrakar/zkpy/actions/workflows/build.yml/badge.svg)
[![PyPI](https://img.shields.io/pypi/v/zkpy)](https://pypi.org/project/zkpy/)
[![docs](https://img.shields.io/badge/docs-docs-blue)](https://sahilmahendrakar.github.io/zkpy/)

[Link](https://github.com/sahilmahendrakar/zkpy)

## Description

ZKPy is a Python library that allows for easy compiling/proving/verifying of zk circuits. It can be primarily implemented as a wrapper of [Circom](https://github.com/iden3/circom) or [SnarkJS](https://github.com/iden3/snarkjs), allowing developers to incorporate their features into Python projects.

Feature wishlist:

- Can perform trusted setup (Powers of Tau and Phase 2)
- Can generate proofs for circuits written in Circom (?)
- Can verify proofs given witness file and verification key
- Implements both Groth16 and PLONK proving schemes
