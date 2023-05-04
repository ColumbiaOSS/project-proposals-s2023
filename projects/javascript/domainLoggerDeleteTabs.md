# Domain Logger - Delete Tabs By Domain

Chrome Extension to Delete Tabs by Domain, and to See a Log Table showing Each Parent Domain and its Corresponding Number of Tabs within a Chrome Window

<img src = "https://img.shields.io/github/license/faizak1/DomainLogger"> <img src = "https://img.shields.io/github/issues/faizak1/DomainLogger">
![Build Status](https://github.com/faizak1/DomainLogger/actions/workflows/build.yml/badge.svg)
[![codecov](https://codecov.io/github/faizak1/DomainLogger/branch/main/graph/badge.svg?token=RUW388KYJF)](https://codecov.io/github/faizak1/DomainLogger)
[![npm](https://img.shields.io/npm/v/domain-logger-delete-tabs-by-domain)](https://www.npmjs.com/package/domain-logger-delete-tabs-by-domain)
[![JSDoc Documentation](https://img.shields.io/badge/docs-jsdoc-blue.svg)](https://faizak1.github.io/DomainLogger/index.html)

## Repo Link

Repo Link: <https://github.com/faizak1/DomainLogger>

## Documentation Link

Documentation Link: <https://faizak1.github.io/DomainLogger/index.html>

## Description

I have created a Chrome extension titled `Domain Logger` to Delete Tabs by Domain, and Show Users a Log Table Displaying Each Parent Domain and its Corresponding Number of Tabs within a Chrome Window (see first link below for details)

## Why it's important

This Chrome extension helps users identify each domain that they have opened in the current Chrome window and delete all tabs under that domain in just one click. Users can also see how many tabs they have open under each parent domain (whether it is Github, Amazon, Youtube, Courseworks, etc) and simply delete all tabs related to the domain they specify, by clicking the "Delete" link corresponding to the particular parent domain they wish to delete.

## Problem Statement

While users can close tabs individually when clearing out their window, this process can become tedious especially for students who can easily have dozens of tabs open while they are studying, watching youtube, shopping online, etc. They can easily get distracted and switch from one tab to another instead of focusing on the task at hand.
Using this chrome extension, with a few simple clicks users can easily remove all domains from their Chrome Window that can be distractions to their current task, which can result in higher productivity. Another advantage of this extension is that if current RAM usage is high, users can reduce this easily with this extension to remove tabs from domains that are no longer needed wih a few simple clicks, thereby reducing the RAM usage of Chrome (which can be utilized for other processes).

## Solution/How It Works

When you start the browser window and unpack this Chrome Extension in "Developer Mode", from that point 'Domain Logger' keeps track of your tabs and domain activity in that window. It categorizes all subdomains that you are visiting under its respective parent domain, logs the total number of tabs under that domain, and gives the option to delete all tabs under that domain with just one click.
For each tab you open under a parent domain and for each tab you close under a parent domain, the count will automatically adjust accordingly. This extension solves the problem since the user will now be able to easily close all irrelavent domains when trying to concentrate, which can help them minimize distraction and become more productive.

## Features

This `Domain Logger` Chrome Extension has 6 key features:

1. User-friendly interface to display all information to user in an easy-to-use manner
2. Logs each parent domain in the current chrome window
3. Displays the number of tabs corresponding to each domain
4. Displays a "delete" link for each domain in the log table to delete all tabs under that domain
5. Real-time monitoring of labs, logs in the domain table update accordingly when adding or deleting any tab
6. Thorough documentation for this Domain Logger Chrome extension
