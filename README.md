# Compute! Paris 2026 Presentation

_Using geojupyter community tools for earth data analysis and visualization at scale in the context of Snow Detection_

This talk will present and demonstrate new Python and Jupyter [ecosystems](https://geojupyter.org/about.html) tools to analyse huge amount of satellite or more generally geospatial data. Our goal is to demonstrate that we are close to be able to propose a Google Earth Engine **open** alternative, that anyone may use and contribute to. It is thus aimed at developers or scientists in the geospatial data analysis field, and will be about technologies such as [JupyterGIS](https://jupytergis.readthedocs.io/en/latest/), Xarray, [Titiler and OpenEO](https://sentinel-hub.github.io/titiler-openeo/). A full use case demonstration on Snow Detection will be showcased at the end of the talk.

Cloud-native technologies and standards are creating new possibilities for geospatial data analysis at global or multi temporal scales. Until recently, Google Earth Engine (GEE) was the only practical solution for scientists wanting to test algorithms at scale and visualize results quickly. With the advancement of the geospatial and Python ecosystems supported by the Pangeo, CNG, and OGC communities, we've seen open-source tools and standards -- including Jupyter, Xarray, Dask, cloud-optimized formats, STAC, and OpenEO -- closing the gap with GEE. Still, there is a shortage of easy-to-use interactive visualization tools for working with modern datacubes and data streams enabled by these new developments.

In this talk, we will present specific work from the GeoJupyter community, based on JupyterGIS for the frontend and TiTiler for the backend, to enable interactive computation at scale.

We'll first give the big picture: the challenge of working with and vizualising the Peta scale datasets in an open and standard way, and how we are closer to building an open source alternative to GEE.

We'll then dive into tools under active developement such as [JupyterGIS](https://github.com/geojupyter/jupytergis) and [Titiler](https://github.com/developmentseed/titiler), show casing their functionnalities and roadmaps. Addtionally, we will show the ease of deployment of JupyterGIS by making use of tools like [JupyterLite](https://github.com/jupyterlite/jupyterlite) and [Notebook.link](https://notebook.link/).

We'll then demonstrate a [CNES (French space agency)](https://cnes.fr/en) use case for snow detection over the Pyrenees mountains. It shows how these technologies can interactively display the results of a computation performed on-the-fly on geospatial data streamed from cloud-optimized and open Sentinel-2 data.
We'll compare alternative methods, including:
- Using OpenEO as the data source, which enables reproducible visualization by serializing a processing graph inside a GIS document.
- Using full Xarray syntax with jupyter-tiler, powered by TiTiler, which enables visualizing a datacube with custom computations.

## How to use this repo

### Slides & website (powered by Quarto)

Use the existing [Pixi](https://pixi.prefix.dev/latest/) tasks to preview the website:

```bash
pixi run preview
```


### Docker

The Docker image builds automatically in GitHub Actions with each push that changes
content in the `docker/` directory.


### Demo

Reference the README in the `demo/` directory.
