
# multi-scale-expansion

## Description

`multi-scale-expansion` is a library for users who are quickly trying to test computer vision models, scaling, and iterating quickly on developing applications using such. The current project has the capability of automatically setting up an image classification model, including the functionality of building a dataset for the user provided a certain file structure for train and test files, as well as conducting fine-tuning on a provided backbone model by adding a classification layer with a number of neurons equal to that of classes. This allows a user to fine-tune a pre-trained state of the art model writing 5 lines of code, instead of developing the whole pipeline (as done so already for the user in my code). Inspiration taken from PyTorch Lightning. 

[Link to repo](https://github.com/ColumbiaMancera/multi-scale-expansion)

## Badges

![Build Status](https://github.com/ColumbiaMancera/multi-scale-expansion/actions/workflows/build.yml/badge.svg)
![image](https://img.shields.io/pypi/l/tensorflow)
[![PyPI](https://img.shields.io/pypi/v/multi-scale-expansion)](https://pypi.org/project/multi-scale-expansion/)
[![Docs](https://img.shields.io/badge/docs-passing-success)](https://columbiamancera.github.io/multi-scale-expansion/)
