# Towards Optimally Weighted Physics Informed Neural Networks in Ocean Modelling

This repository contains the data sets, source code, and results of the paper. The source code is in the form of Jupyter Notebooks and can be executed by installing both Python 3 and Jupyter Notebooks on any platform. All assets are released under the open source [CeCILL license](https://en.wikipedia.org/wiki/CeCILL), see LICENSE file.

## Install instructions

### Requirements

- [Python 3.8](https://www.python.org/downloads/) or newer,
- [Git](https://git-scm.com/downloads), and
- A [Weight and Biases](https://wandb.ai/) (free) account.

### Option 1: Using pip

Install dependecies by running:

```bash
pip install -r requirements.txt
```

and create an instance of jupyter notebooks by:

```bash
jupyter notebook
```

**Note:** This requirements.txt file was automatically generated from the poetry specs by running `poetry export -f requirements.txt --output requirements.txt --without-hashes`.

### Option 2: Using poetry

This is the preferred option if you plan to do a more extensive experimentation.

Install [poetry](https://python-poetry.org) by running (see [instructions](https://python-poetry.org/docs/) if necessary):

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

Install project dependencies in a local `virtualenv` by running in the root of the project:

```bash
poetry install
```

This created a `.venv` virtual environment with all the dependecies. To active it and run an instance of jupyter notebooks run:

```bash
.venv/bin/activate
jupyter notebook
```

## Reproducing results

1. Run `jupyter notebook` and navigate to `Notebooks` to find the code used for the paper.
2. You need to put the WandB key when asked, which you can find under Settings in your WandB account.
3. In `Data` you can find the data sets, and in `Plots` the results and the code to produce the plots of the paper.
