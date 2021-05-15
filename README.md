# Leveraging satellite data and pangeo to investigate the role of Gulf Stream frontal dynamics in ocean productivity
This notebook can be run fully in the cloud via binder by clicking this badge:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/patrickcgray/gulf_stream_productivity_dynamics/main)
It will take a few minutes to provision but will allow a fully interactive coding environment with this notebook and all dependencies.


This notebook can also be run in the pangeo binder for a bit more memory:
[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/patrickcgray/gulf_stream_productivity_dynamics/main)

The Gulf Stream is a dominant physical feature in the North Atlantic influencing the marine ecosystem across trophic levels, yet the physical-biological interactions along this western boundary current are poorly understood. In this work we analyze Gulf Stream physical and biological patterns over multiple years with particular emphasis on how the current's front impacts biology across space and time. We ask specifically how phytoplankton patterns along the front correspond to seasonality and wind with speculation on possible nutrient limitations. This work primarily uses satellite-based sea surface temperature, chlorophyll-a, and sea surface height. Using `xarray` and running in `jupyter` in the cloud allows efficient analysis across many years of satellite data. `holoviz` is used for interactive visualization and data exploration. This work aims to provide insight into the overall role of Gulf Stream frontal features and dynamics in ocean productivity and increase the ease of access, manipulation, and visualization of these highly dimensional and complex datasets.

The primary contributios of this work are:
- collation and visualization of a variety of oceanographic datasets permitting investigation of the Gulf Stream front
- derivation of the Gulf Stream front location ever month for a decade from Sea Surface Height data
- demonstration of an array of scientific computing tools for oceanography analysis
- investigation of the physical and biological properties of the Gulf Stream front over a decade

This notebook and repo was developed in large part for the 2021 [EarthCube](https://www.earthcube.org/) annual meeting.
