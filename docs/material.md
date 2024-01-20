---
title: Session Material
layout: default
nav_order: 3
---

# Session Material

---

Each session consists of four parts. The first part is a slides-based presentation which introduces the Rubin Project and key concepts within the Rubin Science Platform. This is followed by three tutorials that utilise jupyter notebooks to demonstrate how to interrogate the RSP databases, retrieve table and imaging data, and re-analyse some data using a re-configured LSST data processing task.

All the material used during each session is freely available online via the links below. While anyone can *view* the jupyter notebooks on GitHub, they can only be *executed* from within the [Rubin Science Platform](https://data.lsst.cloud/) (RSP) since that is where the required python modules and data repositories reside. As such, anyone who wishes to execute the notebooks will need to have data access rights to log into the RSP. Please also note the the notebooks are also currently set up to use the DP0.2 dataset, although reconfiguring them to use a different dataset would only require a straightforward change of the `repo` an `collection` parameters at the start. 

* Presentation: [Google Slides](https://docs.google.com/presentation/d/1TU5R4Tk8KbkuEGj4Qqk2ok00PMuIUihu32k874-ca9c/edit?usp=sharing)
* Tutorial 1: [Jupyter Notebook](https://github.com/lsst-uk/rsp-uk-notebooks/blob/main/Intro_to_RSP/IntroToRSPSession1.ipynb)
* Tutorial 2: [Jupyter Notebook](https://github.com/lsst-uk/rsp-uk-notebooks/blob/main/Intro_to_RSP/IntroToRSPSession2.ipynb)
* Tutorial 3: [Jupyter Notebook](https://github.com/lsst-uk/rsp-uk-notebooks/blob/main/Intro_to_RSP/IntroToRSPSession3.ipynb)

Further, while not explicitly used during the sessions, an additional notebook is provided that lists what will likely be most popular datasets, and how to retrieve them via the Data Butler:

* Key dataset types: [Jupyter Notebook](https://github.com/lsst-uk/rsp-uk-notebooks/blob/main/Intro_to_RSP/KeyDatasets.ipynb)

Finally, by popular request, here is a link to a page that lists what data are available via LSST's Table Access Protocol service (aka schemas). 

* LSST's TAP Schema Browser: ['Link'](https://dm.lsst.org/sdm_schemas/browser/) 
