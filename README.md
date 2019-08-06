# Practical Data Visualization with Python

## Overview

**Note:** *All views expressed on this site are my own and do not represent the opinions of any entity with which I have been, am now, or will be affiliated.*

This repository contains all materials related to a lecture / seminar I teach on practical data visualization with python. What I mean by "practical" is that the materials herein do not focus on one particularly library or data visualization method; rather, my goal is to empower the consumer of this content with the tools, heuristics, and methods needed to handle a wide variety of data visualization problems. 

This is a work in progress that will be evolving rapidly over the coming weeks and months, so please check back often for new additions and refinements, and if you'd like to contact me, don't hesitate to reach out [via Twitter here](https://twitter.com/ByPaulJ).

## Outline of Materials

In the section below you'll find a brief outline of the content contained in the four sections of this seminar. For each section there is a separate Jupyter notebook of python code containing all the materials for that section. Each notebook will start with a few setup steps--package imports and data prep mostly--that are almost identical between the notebooks, directly after which comes the content for each section.

### Why We Visualize

1. The power of visual data representation and storytelling. 
2. A few principles and heuristics of visualization.
3. The building blocks of visualization explored.

### Overview of Python Visualization Landscape

1. Intro to the visualization ecosystem: python's Tower of Babel.
2. Smorgasbord of packages explored through a single example viz.
3. Quick & dirty (and subjective) heuristics for picking a visualization package.

### Statistical Visualization in the Wild

1. Example business use case of data visualization: debt-to-income ratios explored.
    1. Observational:
        - mean, median, and variance
        - distributions
    2. Inferential:
        - two-sample t-test
        - KS test

### Library Deep-Dive (Plotly)

1. Quick and simple data visualizations with Plotly Express.
    - Mark types, colors, facets, etc.
2. Additional control and complexity with base Plotly.
    - Choropleth maps 
    - Heatmaps 

## Links

- For the main lecture notebook:
    - [Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/main_lecture_nb.ipynb) to the easy-to-view notebook
    - [Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/main_lecture_nb.ipynb) to the GitHub-hosted version of the notebook

- For the data prep notebook:
    - [Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/data_prep_nb.ipynb) to the easy-to-view notebook
    - [Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/data_prep_nb.ipynb) to the GitHub-hosted version of the notebook
    
- For the homework notebook (participant version):
    - [Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/participant_hw_nb.ipynb) to the easy-to-view notebook
    - [Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/participant_hw_nb.ipynb) to the GitHub-hosted version of the notebook
    
## Setup Instructions

- clone this repository locally
- create a virtual environment using `python3 -m venv env`
    - additional information about this [can be found here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)
- activate that virtual environment using `source env/bin/activate`
- install needed packages using `pip install -r requirements.txt`
    - additional information about this [can be found here](https://pip.pypa.io/en/latest/user_guide/#requirements-files)
- run an instance of jupyter lab out of your virutal env using `env/bin/jupyter-lab`
- start by opening and running the `main_lecture_nb.ipynb` file, in which the majority of the content is located