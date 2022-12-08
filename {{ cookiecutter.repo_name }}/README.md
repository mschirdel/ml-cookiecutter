{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Requirements
---------------------

{{cookiecutter.requirements}}

Project Convention
------------------
This project follows the machine learning project development conventions. Please refer this link to find all the project setup and development conventions.

Project Organization
--------------------

    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    |
    ├── Dockerfile         <- Main Dockerfile for building image from projects.
    |
    ├── README.md          <- The top-level README for developers using this project.
    |
    ├── pyproject.toml     <- Python environment managment using poetry.
    |
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── .circleci          <- automated ci pipeline
    │
    ├── .githubs           <- automated github pull request messages
    |
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models artifact for baking in images
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
    ├── scripts            <- automated scripts for building package and deployments
    │
    ├── src                <- Source code for use in this project.
    │   │
    │   ├── configs        <- Scripts to download or generate data
    │   │
    │   ├── customize      <- Scripts to download or generate data
    │   │
    │   ├── dataset        <- Scripts to download or generate data
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    |   |
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │                     predictions
    │   └── utils          <- Scripts to make the backend integrations and utils (job status report, ErrorHandlers)
    │   
    └── tests              <- Pytest codes for unittests
