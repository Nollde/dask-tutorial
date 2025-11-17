# Dask Tutorial

This repository is a minimal and tailored version of a tutorial, which was given at SciPy 2022 in Austin Texas. You can find the full tutorial [here](https://github.com/dask/dask-tutorial). I highly recommend taking a look!

## Prepare

#### 1. You should clone this repository

    git clone https://github.com/Nollde/dask-tutorial

and then install necessary packages.
There are three different ways to achieve this, pick the one that best suits you, and ***only pick one option***.
They are, in order of preference:

#### 2. Create a conda environment

In the main repo directory

    conda env create -f env.yml
    conda activate dask_tutorial

### Launch Jupyter

From the repo directory

    jupyter lab

You are welcome to use Jupyter notebook if you prefer, but we'll be using lab in the live tutorial.

## Outline

0. [Overview](00_overview.ipynb) - dask's place in the universe.

1. [Dataframe](01_dataframe.ipynb) - parallelized operations on many pandas dataframes spread across your cluster.

2. [Array](02_array.ipynb) - blocked numpy-like functionality with a collection of numpy arrays spread across your cluster.

3. [Delayed](03_dask.delayed.ipynb) - the single-function way to parallelize general python code.

4. [Deployment/Distributed](04_distributed.ipynb) - Dask's scheduler for clusters, with details of how to view the UI.

5. [Distributed Futures](05_futures.ipynb) - non-blocking results that compute asynchronously.

6. Conclusion
