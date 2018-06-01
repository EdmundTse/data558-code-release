# DATA 558 Code Release
>This repository serves as my submission for a homework assignment for the Spring 2018 DATA 558 Statistical Machine Learning course at the University of Washington.

In the Jupyter notebook, I implemented a linear support vector machine that uses a squared hinge loss function and an L2-regularisation term. It is a binary classifier, so I converted it to a multiclass classifier using a one-vs-rest strategy and also included cross validation to search for the best coefficient to use for the regularisation term.

When this was tested against both a simulated (randomly generatedly) dataset and a real example dataset in scikit-learn, I found that the trained scikit-learn classifiers performed better than my implementation.

## Where to download data to run the examples
The dataset I used was one that is built into scikit-learn. The dataset will be downloaded automatically the first time `load_digits()` function is called.

## How to run the examples
The examples are supplied as a [Jupyter](http://jupyter.org/) notebook. Just download and import the .ipynb file to a Jupyter environment.

An easy way to get started running the notebook is to import it into an online platform of your choice, including:
* [Microsoft Azure Notebooks](https://notebooks.azure.com/)
* [Colaboratory](https://colab.research.google.com/)
* [Kaggle Kernels](https://www.kaggle.com/kernels)

Or, run it a local Jupyter environment on you own computer if that's already set up.
