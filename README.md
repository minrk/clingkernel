# Cling Kernel

C++ Kernel for Jupyter with Cling.

## Merged into cling

**This repo is no longer maintained, as it has been [merged into cling itself](https://github.com/root-mirror/cling#jupyter)**

## Old stuff:

You will probably need to specify the path to cling with the `CLING_EXE` env variable.

**Note:** This currently requires master of everything IPython and Jupyter because that's what I use,
but I'll clean that up so it works on 3.x.

## Install

To install the kernel:

    jupyter kernelspec install cling

or for IPython/Jupyter < 4:

    ipython kernelspec install cling
