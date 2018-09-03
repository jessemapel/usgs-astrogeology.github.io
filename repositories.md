---
title: Repositories
permalink: /repositories/
layout: page
---

## Community Sensor Model
- [Community Sensor Model (csm)](https://github.com/USGS-Astrogeology/csm): We maintain a fork of the Community Sensor Model API that is built using [TravisCI](https://travis-ci.org/USGS-Astrogeology/conda-libcsm).
- [CSM-SWIG](https://github.com/USGS-Astrogeology/CSM-Swig): While the CSM is developed and accessible via C++, we also maintain [SWIG](https://github.com/swig/swig) wrappers. Currently, these are built for Python. As the CSM is an API, this wrapper will work for any CSM compliant implementation. If you would like to see another SWIG supported language added, get in touch with an issue or PR!
- [CSM-CameraModel](https://github.com/USGS-Astrogeology/CSM-CameraModel): This repository contains the ASC maintained CSM compliant sensor models.
- [SensorUtils]
- [SensorUtils-SWIG]
- [Pfeffernusse]

## C++
- [ISIS3]

## Python
- [autocnet](https://github.com/USGS-Astrogeology/autocnet): A library for the automated extraction and matching of image correspondences using computer vision and photogrammetry techniques. API Documentation is available [here](https://usgs-astrogeology.github.io/autocnet/).
- [plio](https://github.com/USGS-Astrogeology/plio): Is a file i/o library, initially built upon GDAL that has since been expanded to support a wide range of planetary data sets. API documentation is available [here](https://usgs-astrogeology.github.io/plio).
- [plurmy](https://github.com/USGS-Astrogeology/plurmy): At ASC we utilize a the Slurm workload manager on our cluster. We often want to submit jobs from without a python script. This library provides simple job submission functions.

## Docker
We utilize docker extensively for research tasks, development, and service deploys. Our images are stored under version control on GitHub and made available using [DockerHub](https://hub.docker.com/u/usgsastro/dashboard/).
- [miniflask](https://github.com/USGS-Astrogeology/docker_miniflask): Is a template image that we build flask based web services on top of.


## Conda / Build / 3rd Party Dependencies
We utilize [anaconda cloud](https://anaconda.org/usgs-astrogeology/dashboard) to deploy many of our projects.
