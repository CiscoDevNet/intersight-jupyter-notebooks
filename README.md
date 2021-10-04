[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/intersight-jupyter-notebooks)

# Intersight Jupyter Notebooks
Experimental collection of Cisco Intersight Jupyter notebooks that exercise the Intersight API's

## Requirements

Here are a few things you'll need to take advantage of the Jupyter Notebooks in this repository:

* You'll need Jupyter Notebook installed in your environment.
* Access to a Cisco Intersight account
* An Intersight API Key

## Notebooks in this Repo

The Jupyter Notebooks in this repo contained detailed steps to accomplish short tasks in Python and PowerShell. The idea is to familiarize you with how to use the Python SDK and PowerShell to programmatically interact with Cisco Intersight. Each notebook is self-contained with documentation and live code examples. As such, you can copy the repo point it to your environment (see requirements above) and expand on the examples as needed.

Jupyter Notebook's design is not being an IDE. Its strengths are providing documentation alongside live code. Once you master the concept and get something working, you can always copy/paste the code into your IDE of choice.

If you are new to Jupyter Notebook, the upcoming sections describe what it is along with instructions and download links for getting started.

> Jupyter Notebook is used frequently in the Data Science community. As such, data sets and models are discussed and are usually part of a Jupyter Notebook. That is not the case here since we are using the tool to provide small examples and show you how you can develop core pieces of code in smaller more manageable pieces.

## About Jupyter Notebook

Jupyter notebook is an interactive, web-based notebook for interactive computing. It combines documentation along with live, executable code on a web page. Thus, code is executed in a browser as seen below.

![Sample Jupyter Notebook Screenshot](images/jupyter-sample-screenshot.png)


> Notebook files are stored in files with a `*.ipynb` extension which are interactive. However when `*.ipynb` files are posted to GitHub, they are rendered as static (non-interactive) HTML pages. That means you can't interact with the pages directly from GitHub. Instead, the `*.ipynb` files are interactive when you run them on your local machine (or using Jupyter Hub which is out of scope for this discussion.)

## Install Anaconda and Jupyter Notebook

First, [install Anaconda](https://docs.anaconda.com/anaconda/install/) as this makes the next installation steps much easier. You can install Jupyter Notebook by following instructions on the [Jupyter Notebook site](https://jupyter.org/install). The page includes a [link](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) to a more comprehensive installation guide, if needed, with instructions for installing Jupyter Notebook using `conda`, `mamba`, `pip`, `pipenv`, and Docker.

## Multiple Language Support

Jupyter Notebook supports languages in addition to Python. For example, [you can add PowerShell](https://devblogs.microsoft.com/powershell/public-preview-of-powershell-support-in-jupyter-notebooks/) and then use PowerShell syntax in each cell. In fact, the notebooks in this repo strive to provide examples in both Python and PowerShell.

>A quick search about languages supported by Jupyter Notebook will turn up a current list so we do not cover languages in addition to Python and PowerShell.

## Getting Started

Now that Jupyter Notebook is installed on your machine, clone this repo and open the notebooks of interest to you. Feel free to modify the code snippets and experiment.