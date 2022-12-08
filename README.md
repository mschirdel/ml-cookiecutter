# Cookiecutter Machine Learning 

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._

This repository has been forked from the following homepage.
#### [Project homepage](http://drivendata.github.io/cookiecutter-data-science/)


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5+
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

    python3 -m cookiecutter -c main https://github.com/MahdyShirdel/cookiecutter-ml.git

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── {{ cookiecutter.repo_name}}                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── dataset           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── dsconfig       <- Scripts to set the ds configurations
    │   │   └── config.py
    |   |
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    |   |
    |   ├── integration       <- Scripts to make the backend integrations (job status report, ErrorHandlers)
    │   │   └── progress_tracker.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict.py
    │   │   └── train.py
    │   │
    │   └── vtk  <- Scripts to create exploratory and results oriented visualizations (visualiztion toolkit)
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


```

### Installing development requirements
------------

    pip install -r requirements.txt

### Running the tests
------------

    py.test tests
