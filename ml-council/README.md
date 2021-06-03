# ml-council : a data science project
==============================

Analysis of  purchase cards transactions from the Birmingham City Council with ML-methods.

## Dataset
Not obliged by law but under the behalf of a Code of Recommendations for Data Transparency, the city is publishing the monthly expenses above $500
[Official website of dataset B. City council](https://data.birmingham.gov.uk/dataset/purchase-card-transactions)

## Business Problem Analysis

1. The council might be interested in gaining insights on the expenditures profiles to therefore mitigate bad usage. 
2. Forecasting future behaivoiour, the council  can plan better its budget and its providers improve their market understanding.

Using a collection of purchase card transactions for the Birmingham City Council. this project aims  the following tasks:
* (Clustering) Discovering profiles (whether the case) 
* (Forecasting) Try to guess future transactional behaviors


## Project basic structure

* On first stage: We will provide a first set of notebooks gathering the basic ML-workflow: Preprocessing Data, Exploratory data-analysis (EDA), model & validation and 1.council_preprocessing.ipynb 
2.council_EDA.ipynb 
3-council_model-clustering.ipynb 
4-council_model-forecasting.ipynb 
* On second stage  We will provide a ready-to-use Proof-of-concept  using a Gradio or parametizable notebook (Papermill)

# Repository Organization
------------

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
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
