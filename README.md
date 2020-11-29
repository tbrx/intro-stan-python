# Introductory examples using Stan from Python

This was tested using Python 3.7.9 and `pystan==2.18.0.0`.

To run the notebooks, you will additionally need to install the following packages, e.g. via pip:

```
pip install jupyter arviz matplotlib seaborn scipy
```

## Running on Google Colab

These notebooks can be run on Google Colab. There is one important edit: the `arviz` package is not included by default in Colab, so you will need to add the following line to the top of the very first cell in each notebook:

```
!pip install arviz
```

To load these notebooks in Colab, you can use the import tool at https://colab.research.google.com/github/tbrx/intro-stan-python/. Note that this will load them READ-ONLY, if you want to save changes you need to first click the button in the toolbar to copy them to your own Drive. The notebooks are completely self-contained, so this should work fine.
