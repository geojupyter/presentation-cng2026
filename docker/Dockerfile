FROM pangeo/pangeo-notebook:latest

RUN mamba install --yes -c conda-forge -n ${CONDA_ENV} \
    "jupytergis-tiler==0.16.6" \
    dask-kubernetes \
    eodag \
    eoreader \
    leafmap \
    libgdal-jp2openjpeg \
    odc-stac \
    openeo \
    pystac \
    xdem \
    && mamba clean -yaf
