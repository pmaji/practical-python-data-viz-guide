# Practical Data Visualization with Python

## Overview

*All views expressed on this site are my own and do not represent the opinions of any entity with which I have been, am now, or will be affiliated.*

This repository contains all materials related to a lecture / seminar I teach on practical data visualization with python. What I mean by "practical" is that the materials herein do not focus on one particular library or data visualization method; rather, my goal is to empower the consumer of this content with the tools, heuristics, and methods needed to handle a wide variety of data visualization problems. 

If you have questions, comments, or suggested alterations to these materials, please [open an issue](https://github.com/pmaji/practical-python-data-viz-guide/issues) here on GitHub. Also, don't hesitate to reach out [via Twitter here](https://twitter.com/ByPaulJ).

## Outline of Materials

Below you'll find a brief outline of the content contained in the four sections of this seminar, along with notebook links, and an example visualization from each section. For each section there is a separate notebook of python code containing all the materials for that section. Each notebook will start with a few setup steps--package imports and data prep mostly--that are almost identical between the notebooks, directly after which comes the content for each section. For information about the data used in these materials, check out the `data_prep_nb.ipynb` notebook, the easy-to-view version of which is [hosted here](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/data_prep_nb.ipynb).

### Section 1: Why We Visualize

[Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_1_main_nb.ipynb) to the easy-to-view notebook for this section of material.
<br>
[Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_1_main_nb.ipynb) to the GitHub-hosted notebook for this section of the material.

1. The power of visual data representation and storytelling. 
2. A few principles and heuristics of visualization.
3. The building blocks of visualization explored.

**Example Visualization from this Section:**

<p align="left">
  <img width="600" height="300" src="https://raw.githubusercontent.com/pmaji/practical-python-data-viz-guide/master/media/for_readme/overlapping_pdf_viz.jpg"></img>
</p>

### Section 2: Overview of Python Visualization Landscape

[Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_2_main_nb.ipynb) to the easy-to-view notebook for this section of material.
<br>
[Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_2_main_nb.ipynb) to the GitHub-hosted notebook for this section of the material.

1. Intro to the visualization ecosystem: python's Tower of Babel.
2. Smorgasbord of packages explored through a single example viz.
3. Quick & dirty (and subjective) heuristics for picking a visualization package.

**Example Visualization from this Section:**

<p align="left">
  <img width="600" height="300" src="https://raw.githubusercontent.com/pmaji/practical-python-data-viz-guide/master/media/for_readme/basic_seaborn_scatter_viz.jpg"></img>
</p>

### Section 3: Statistical Visualization in the Wild

[Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_3_main_nb.ipynb) to the easy-to-view notebook for this section of material.
<br>
[Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_3_main_nb.ipynb) to the GitHub-hosted notebook for this section of the material.

1. Example business use case of data visualization:
    1. Observational:
        - mean, median, and variance
        - distributions
    2. Inferential:
        - parametric tests
        - non-parametric tests

**Example Visualization from this Section:**

<p align="left">
  <img width="600" height="300" src="https://raw.githubusercontent.com/pmaji/practical-python-data-viz-guide/master/media/for_readme/ecdf_ks_test_viz.jpg"></img>
</p>

### Section 4: Library Deep-Dive (Plotly)

[Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_4_main_nb.ipynb) to the easy-to-view notebook for this section of material.
<br>
[Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/part_4_main_nb.ipynb) to the GitHub-hosted notebook for this section of the material.

1. Quick and simple data visualizations with Plotly Express.
2. Additional control and complexity with base Plotly.

**Example Visualization from this Section:**

<p align="left">
  <img width="600" height="300" src="https://raw.githubusercontent.com/pmaji/practical-python-data-viz-guide/master/media/for_readme/heatmap_plotly_viz.jpg"></img>
</p>

### Homework Exercises

There is a homework exercise associated with these materials, for those interested. 

- [Here is the link](https://nbviewer.jupyter.org/github/pmaji/practical-python-data-viz-guide/blob/master/notebooks/participant_hw_nb.ipynb) to the easy-to-view notebook (participant version)
- [Here is the link](https://github.com/pmaji/practical-python-data-viz-guide/blob/master/notebooks/participant_hw_nb.ipynb) to the GitHub-hosted version of the notebook (participant version)
    
## Setup Instructions

- clone this repository
- create a virtual environment using `python3 -m venv env`
    - additional information about this [can be found here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)
- activate that virtual environment using `source env/bin/activate`
- install needed packages using `pip install -r requirements.txt`
    - additional information about this [can be found here](https://pip.pypa.io/en/latest/user_guide/#requirements-files)
- run an instance of jupyter lab out of your virutal env using `env/bin/jupyter-lab`
- opening and run the four main files of content for this course--one for each section:
    - `part_1_main_nb.ipynb`
    - `part_2_main_nb.ipynb`
    - `part_3_main_nb.ipynb`
    - `part_4_main_nb.ipynb`