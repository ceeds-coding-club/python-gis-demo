# Python - geospatial analysis using `geopandas`, `rasterio` and `rioxarray`

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ceeds-coding-club/python-gis-demo/HEAD?filepath=python-gis-notebook.ipynb)

This repo stores resources from the Python GIS demo which was initially run on 13 April 2021 by [Sam Harrison](https://github.com/samharrison7). The goal of the demo was give an introduction to working with geospatial data in Python using `geopandas`, `rasterio` and `rioxarray`.

## Resources from the demo

- Slides from the demo in [HTML](./python-gis-notebook.slides.html) or [PDF](./python-gis-notebook.slides.pdf) format.
- [A video recording of the session is available here.](https://ukri.zoom.us/rec/share/ZtoibIO4xgP5G-6_V7fJreY-VGoSL8BhpvJtC0xoDNNmQaL_CqsSuDAsemdnUatm.cg4hL8tZV36mWb8D?startTime=1618315604000)
- The Jupyter Notebook used to create the slides [can be launched in Binder](https://mybinder.org/v2/gh/ceeds-coding-club/python-gis-demo/HEAD?filepath=python-gis-notebook.ipynb) (note that viewing the `.ipynb` file via GitHub isn't recommended as images don't show correctly).
- The [environment.yaml](./environment.yaml) file can be used to create a Conda environment with all the requirement to run the notebook (Binder used this file). If you have Conda installed, run `conda env create -f environment.yaml` from this directory.
- The data used in the demo is stored in [data/](./data).

## External resources

- This [Carpentries Incubator "Introduction to Geospatial Raster and Vector Data with Python"](https://carpentries-incubator.github.io/geospatial-python/aio/index.html) is a great introductory resource. It is still a work in progress, but what is there is good.
- [Automating GIS-processes from the University of Helsinki](https://automating-gis-processes.github.io/site/) is an extensive course on GIS programming in Python. It focusses mainly on vector data, but there is a section on rasters to.
- The [GeoPandas](https://geopandas.org/index.html), [Rasterio](https://rasterio.readthedocs.io/en/latest/) and [Rioxarray](https://corteva.github.io/rioxarray/stable/) docs are all useful.