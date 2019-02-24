# Research Project Template

A standardized template I can use to generate new repos for research projects.

### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/lbybee/research_project_template


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── LICENSE
├── Makefile           <- Makefile for building project completely
├── README.md          <- The top-level README for developers using this project.
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── notes              <- Latex scratch notes
│
├── scratch            <- Exploratory code. Naming convention is a date (for ordering),
│                         the creator's initials, and a short `_` delimited description, e.g.
│                         `20190201_LB_initial_data_exploration.py`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│
└── src                <- Source code for use in this project.
    ├── __init__.py    <- Makes src a Python module
    │
    ├── collection          <- Scripts to download or generate data
    │
    ├── data_prep           <- Scripts to turn raw data into features for modeling
    │
    ├── estimation          <- Scripts to estimate models
    │
    └── visualization       <- Scripts to create visualizations
```
