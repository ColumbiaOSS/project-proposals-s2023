# Multithreading Library in C++

[libmt](https://github.com/afsong/libmt)

![GitHub release (latest by date)](https://img.shields.io/github/v/release/afsong/libmt?color=orange)
[![shields.io](https://img.shields.io/badge/doc-blue)](https://afsong.github.io/libmt/)
![GitHub](https://img.shields.io/github/license/afsong/libmt)
[![Actions Status](https://github.com/afsong/libmt/workflows/MacOS/badge.svg)](https://github.com/afsong/libmt/actions)
[![Actions Status](https://github.com/afsong/libmt/workflows/Ubuntu/badge.svg)](https://github.com/afsong/libmt/actions)
![shields.io](https://img.shields.io/github/issues/afsong/libmt)
[![codecov](https://codecov.io/gh/afsong/libmt/branch/main/graph/badge.svg)](https://codecov.io/gh/afsong/libmt)
[![codeql](https://github.com/afsong/libmt/workflows/CodeQL/badge.svg)](https://github.com/afsong/libmt/actions)

## Motivation

STL does not provide much beyond basic threads and mutexes in terms of multithreading support. My goal is to provide common constructs that are useful such as thread pools and job queues.

The main focus as of now it to build something modular, that fits general purpose programming. After that, I'm planning on improving performance if time allows.

## Basic Idea

I want to first start by considering which constructs are popular and often used. After that, I want to implement a type-safe implementation using modern C++20 features such as Concepts.

## Description

Currently, the implementation includes three classes:
    - thread pool
    - circular buffer
    - job queue

In addition to this, it also has CMake integration and Conan as registry. You can find more info in the github repo linked above!
