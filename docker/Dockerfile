FROM pangeo/pangeo-notebook:latest

RUN mamba install --yes -c conda-forge -n ${CONDA_ENV} \
    "jupytergis==0.16.7" \
    dask-kubernetes \
    eodag \
    eoreader \
    jupyter-tiler \
    leafmap \
    libgdal-jp2openjpeg \
    odc-stac \
    openeo \
    pystac \
    xdem \
    && mamba clean -yaf
