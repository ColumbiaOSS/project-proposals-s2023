# age3d

[![](https://img.shields.io/badge/project-link-green)](https://github.com/A-Chaudhary/age3d)

[![Build Status](https://github.com/A-Chaudhary/age3d/workflows/Build%20Status/badge.svg?branch=main)](https://github.com/A-Chaudhary/age3d/actions?query=workflow%3A%22Build+Status%22)
[![GitHub](https://img.shields.io/github/license/A-Chaudhary/age3d)](https://github.com/A-Chaudhary/age3d/blob/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/age3d)](https://pypi.org/project/age3d/)
[![Documentation Status](https://readthedocs.org/projects/age3d/badge/?version=latest)](https://age3d.readthedocs.io/en/latest/?badge=latest)

[![Documentation](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white)](https://a-chaudhary.github.io/age3d/)

## Description

`age3d` is a library for aging 3d models through the effects of weather. It takes 3d model files and erodes them down simulating rain particles.

Features:

- Conversion of `.stl` to `TriangleMesh`
- Allows for Segmentation of Mesh Vertices based on Height Params
- Erodes Mesh by Simulating Erosion Particles
  - Customizable Number of Particles
  - Customizable Lifetime of Particles
  - Performs Raycasting Computation to Only Remove Material
