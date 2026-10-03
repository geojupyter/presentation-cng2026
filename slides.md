---
title: "🌐 GeoJupyter 🌐<br/>@<br/>🌥️ CNG '26 🌥️"
subtitle: |
  _Exploring more approachable geospatial data workflows as a community_
authors:
  - name: "Matt Fisher"
    orcid: "0000-0003-3260-5445"
    affiliations:
      - "Schmidt DSE @ UC Berkeley"
  - name: "Guillaume Eynard-Bontemps"
    orcid: "0000-0002-5210-0164"
    affiliations:
      - "Centre National d'Etudes Spatiales (CNES)"
title-slide-attributes:
  data-notes: |
    Good morning!
format:
  revealjs:
    from: "markdown+emoji"
    theme: "white"
    css: "assets/css/slides.css"
    footer: "[Home](/) | [Source](https://github.com/geojupyter/presentation-cng2026) | [geojupyter.org](https://geojupyter.org)"
    auto-stretch: true
    slide-number: true
---

## :wave: Hi, I'm Matt! Website: [`mattz.cool`](https://mattz.cool) {.smaller .even-smaller-header}

:::::::::columns
::::::{.column width=50%}
:::evenly-spaced
:computer: Research Software Engineer ([RSE](https://us-rse.org/)), Community Manager @ [Schmidt DSE, UC
Berkeley](https://dse.berkeley.edu/)

:people_holding_hands: Community Engagement Manager

:snowflake: Previously at [National Snow & Ice Data Center (NSIDC)](https://nsidc.org)

:open_hands: Open source maintainer & contributor:
[jupytergis](https://github.com/geojupyter/jupytergis),
[jupyter-tiler](https://github.com/geojupyter/jupyter-tiler),
[earthaccess](https://github.com/nsidc/earthaccess),
several [conda-forge](https://conda-forge.org/) packages,
more!

:open_hands: :open_book: :brain:
:seedling: :notes: :drum: :musical_keyboard: :dog:
:::
::::::

::::::{.column width=50%}
![[geojupyter.github.io/presentation-cng2026](https://geojupyter.github.io/presentation-cng2026)](/assets/images/qr.svg){width=100%}
::::::
:::::::::


:::notes
Emojis: Open source, documentation, optimizing for cognitive load, plants and nature,
musical instruments, dogs!
:::


## :wave: Hi, I'm Guillaume! Github: [guillaumeeb](https://github.com/guillaumeeb) {.smaller .even-smaller-header}

:::::::::columns
::::::{.column width=50%}
:::evenly-spaced
:computer: :space_invader: Satellite image processing and distributed data analysis expert at [CNES](https://cnes.fr/en)

:snowflake: :floppy_disk: Maintaining snow detection algorithm ([Let it snow](https://gitlab.orfeo-toolbox.org/remote_modules/let-it-snow)), and improving CNES [library ecosystem](https://geodes-tools.cnes.fr/en/) (from the outside mainly)

:earth_asia: Member of [Pangeo community](https://pangeo.io/) for 8 years (missed the start)

:factory: Previously head of the CNES computing center team, specialized in Big Data tools (Spark, Dask)

:open_hands: Open source supporter, funding and small contributor:
[dask](https://github.com/dask/dask),
[dask-jobqueue](https://github.com/dask/dask-jobqueue),
[Let it snow](https://gitlab.orfeo-toolbox.org/remote_modules/let-it-snow),

:open_hands: :satellite: :brain: :earth_asia:
:tent: :runner: :snowboarder: :guitar: :wine_glass: :bridge_at_night:
:::
::::::

::::::{.column width=50%}
![[geojupyter.github.io/presentation-cng2026](https://geojupyter.github.io/presentation-cng2026)](/assets/images/qr.svg){width=100%}
::::::
:::::::::


:::notes
Emojis: Open source, Satellite, optimizing for cognitive load, earth observation,
hiking, running, mountain snow climbing, guitar, party!
:::


# :earth_asia: GeoJupyter community overview

:::{style="font-size: 1.8em"}
:zap: Lightning version!
:::

:link: [geojupyter.org](https://geojupyter.org/)


## GeoJupyter community overview {.smaller}

:::::::::columns

::::::{.column width="48%"}
:::elevator-pitch
<br />
<br />

<hr />
GeoJupyter is an open and community-owned effort to
[reimagine geospatial interactive computing experiences _within the Jupyter architecture_]{.jupyter-orange}
to enable more people to confidently engage with geospatial data.
<hr />

<br />
<br />

Many players!!!
:::
::::::

::::::{.column width="4%"}
::::::

::::::{.column width="48%"}
![GeoJupyter is **not** software; it’s a **community** which will build many things together!](/assets/images/venn-diagram.svg)
::::::

:::::::::


## Our values

:::evenly-spaced
:open_hands: **Open source & open science** - geospatial data is important to everyone!

:cartwheeling: **Approachability** and **playfulness**, like desktop GIS tools

:feather: **Flexibility** and **reproducibility**, like coding methods

:performing_arts: **Collaboration** and **storytelling**, like Jupyter Notebooks
:::


## GeoJupyter community overview {.smaller}

### Geospatial data practice for the modern era

**Geospatial data is everywhere and matters for everyone! 🚚🚢🗺️🧪🌏**

:::evenly-spaced
:handshake: Real-time collaboration (like Google Docs)

:recycle: Reproducibility (by default!)

:leaves: Accessibility (transition to new ways of working, including reproducibility)

:cloud: Cloud-native (computing, data formats)

:robot: AI :scream: :boom: (risks & opportunities)

<br />
<br />
:::

## GeoJupyter community overview {.smaller}

### Open, participatory development

:::evenly-spaced
:revolving_hearts: User-centered & user-led

:hugs: Welcoming (like Jupyter)

:flashlight: Exploring: finding & opening hidden doors

:japanese_castle: Data & computational sovereignty

<br />
<br />
:::


## GeoJupyter community overview {.smaller}

### Partners :scientist: :teacher: :technologist:

* QuantStack - Open source for science
* Maryam Hosseini - urban systems, computer vision, & open source
* Clancy Wilmott - Critical Cartography, Geovisualisation and Design
* Qiusheng Wu - Geospatial, AI, & education
* Sarah Chasins & Parker Zeigler - cartography, CS, & open source
* Nancy Thomas & Iryna Dronova - Berkeley Geospatial Innovation Facility
* Carl Boettiger - Geospatial, AI, & education
* Benny Szeghy & Esha Potharaju - GeoJupyter interns
* Friends & neighbors: BIDS, MyST, JupyterHub, earthaccess, DevSeed, Pangeo, 2i2c, Clark
  University, Stanford, Simula, CNES, ESA
* **MANY MORE!!!**


# :building_construction: Projects in the GeoJupyter community


## JupyterGIS

![A screenshot of JupyterGIS](/assets/images/jupytergis-screenshot.jpg)


## :handshake: Collaborate

![Two users collaborating in real-time on a JupyterGIS project ([QuantStack](https://quantstack.net/slides))](/assets/images/jupytergis-collab-cursors.gif){width=100%}

:::notes
Thanks again to the modular Jupyter architecture, we can leverage
the `jupyter-collaboration` extension, which enables real-time collaboration on
Notebooks, to enable real-time collaboration on a map.

Here you can see two users' cursors (emphasized for visibility) on the same map.
:::


## :handshake: Collaborate: Follow a user

![One user following another in real-time on a JupyterGIS project ([QuantStack](https://quantstack.net/slides))](/assets/images/jupytergis-collab-follow.gif){width=100%}

:::notes
In this graphic, one user is following another user's viewport activity in real time.
:::


## :handshake: Collaborate: Edit together

![Two users editing a shared map ([QuantStack](https://quantstack.net/slides))](/assets/images/jupytergis-collab-edit.gif){width=100%}

:::notes
Here you can see collaborators editing a shared map.
:::


## :handshake: Collaborate: Annotations

![Two users having a conversation with spatial context through annotations ([QuantStack](https://quantstack.net/slides))](/assets/images/jupytergis-collab-annotate.gif){width=100%}

:::notes
Here you can see collaborators having a spatially aware conversation, like
comments in Google Docs.
:::


## :crystal_ball: Discover data with STAC (WIP)

![Browsing a STAC catalog in JupyterGIS ([eo science for society blog](https://eo4society.esa.int/2025/10/16/jupytergis-breaks-through-to-the-next-level/))](https://eo4society.esa.int/wp-content/uploads/2025/10/screenshot-5.png)

:::notes
We can discover data using Spatio Temporal Asset Catalogs, or "STAC catalogs",
a modern standard for computer interface with data catalogs.

This is a work in progress that will continue to evolve over time!
:::


## Jupyter Tiler

![A diagram of `jupyter-tiler`](/assets/images/jupyter-tiler-diagram.svg)


---

![Animation of an Xarray-computed layer with `jupytergis-tiler`](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*LoISLf6L4GKZZgl2a9jlew.gif)


## Experiment: reproducible viz -> Notebook workflows

![Reproducible workflow from viz-land to Notebook-land (:clap: Benny & Esha!)](assets/images/reproducible-viz-to-notebook-workflow.gif)


## [Future](https://github.com/geojupyter/initiatives/issues?q=sort%3Aupdated-desc%20is%3Aissue%20is%3Aopen%20label%3A%22type%3A%20initiative%22)

:::evenly-spaced
:open_book: **"Scrollytelling"**
([initiative](https://github.com/geojupyter/initiatives/issues/19))

:robot: GeoAI :thinking:
([initiative](https://github.com/geojupyter/initiatives/issues/14), [prototype](https://github.com/geojupyter/jupyter-geoagent),
[talk](https://www.youtube.com/watch?v=_5yuXU5salY))

:rock: Richer geospatial primitives for Python
([initiative](https://github.com/geojupyter/initiatives/issues/18))

:mountain: Reproducible "geoprocessing" (following lessons learned from interns' exploration) ([initiative](https://github.com/geojupyter/initiatives/issues/3))

:art: Reusable symbology editor component?
([initiative](https://github.com/geojupyter/initiatives/issues/8))

:teacher: Example datasets for education
([initiative](https://github.com/geojupyter/initiatives/issues/9))
:::
