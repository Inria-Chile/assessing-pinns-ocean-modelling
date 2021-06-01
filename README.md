![Inria logo](https://avatars.githubusercontent.com/u/4306190?s=200&v=4)
# Towards Optimally Weighted Physics Informed Neural Networks in Ocean Modelling

This repository contains the data sets, source code, and results of the paper. The source code is in the form of Jupyter Notebooks and can be executed by installing both Python 3 and Jupyter Notebooks on any platform. All assets are released under the CeCILL license, see LICENSE file.

## Usage
Make sure to have the following dependencies installed:

- [Python 3.8](https://www.python.org/downloads/) or newer
- [Anaconda](https://docs.anaconda.com/anaconda/install/)
- [Git](https://git-scm.com/downloads)
- [WandB](https://wandb.ai/) account

Then execute get the Git repository:
```bash
$ git clone https://github.com/Inria-Chile/assessing-pinns-ocean-modelling
$ cd assessing-pinns-ocean-modelling
```

Create a virtual environment and install the dependencies:

```bash
$ conda env create -f environment.yml
$ conda activate pinns
```

Start up Jupyter Notebooks:

```bash
$ jupyter notebook
```

From here you can navigate to `Notebooks` to find the code used for the paper. You need to put the WandB key when it asks you, which you can find under Settings in your WandB account.

In `Data` you can find the data sets, and in `Plots` the results and the code to produce the plots of the paper.
