# Multithreading Library in C++

[libmt](https://github.com/afsong/libmt)

## Motivation

STL does not provide much beyond basic threads and mutexes in terms of multithreading support. My goal is to provide common constructs that are useful such as thread pools and job queues.

The main focus as of now it to build something modular, that fits general purpose programming. After that, I'm planning on improving performance if time allows.

## Basic Idea

I want to first start by considering which constructs are popular and often used. After that, I want to implement a type-safe implementation using modern C++20 features such as Concepts.
