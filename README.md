# Leveraging satellite data and pangeo to investigate the role of Gulf Stream frontal dynamics in ocean productivity

Authors:
[Patrick C. Gray](https://orcid.org/0000-0002-8997-5255) & [David W. Johnson](https://orcid.org/0000-0003-2424-036X)

### Running the Notebook
This notebook can be run fully in the cloud via binder by clicking this badge:    [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/patrickcgray/gulf_stream_productivity_dynamics/main)

This notebook can also be run in the pangeo binder for additional memory: [![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/patrickcgray/gulf_stream_productivity_dynamics/main)

It may take a few minutes to provision, but these Binder links create a fully interactive coding environment with this notebook and all dependencies included. On occasion there can be a network issue with downloading the necessary packages. If you have any issues try the other option or re-click to relaunch binder.

## Overview

The Gulf Stream is a dominant physical feature in the North Atlantic, influencing the marine ecosystem across trophic levels, yet the physical-biological interactions along this western boundary current are poorly understood. In this work we analyze Gulf Stream physical and biological patterns over multiple years with particular emphasis on how the current's front impacts biology across space and time. We ask specifically how phytoplankton patterns along the front correspond to seasonality and wind with speculation on possible nutrient limitations. This work primarily uses satellite-based sea surface temperature (SST), chlorophyll-a (chla), and sea surface height (SSH) data. Using `xarray` and running in `jupyter` in the cloud allows efficient analysis across many years of satellite data and `holoviz` enables interactive visualization and data exploration. Basing this work on a [pangeo Docker image](https://github.com/pangeo-data/pangeo-docker-images) allows easy reproducibility and a robust set of packages for scientific computing. This work aims to provide insight into the overall role of Gulf Stream frontal features and dynamics in ocean productivity and increase the ease of access, manipulation, and visualization of these highly dimensional and complex datasets.

### The primary contributions of this work are:
- collation and visualization of a variety of oceanographic datasets permitting investigation of the Gulf Stream front
- derivation of the Gulf Stream front location every month for a decade from Sea Surface Height data
- demonstration of an array of scientific computing tools for oceanography analysis
- investigation of the physical and biological properties of the Gulf Stream front over a decade

### Citation
Gray, P.C., & Johnston D.W., 2021. Leveraging satellite data and pangeo to investigate the role of Gulf Stream frontal dynamics in ocean productivity. Accessed on <date> at https://github.com/earthcube2021/ec21_gray_etal
