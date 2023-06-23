<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Remote Data Access with Xarray Cookbook

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/erin6541/xarray-cb/HEAD?labpath=notebooks%2Fxarray-cb.ipynb)

This Project Pythia Cookbook covers using Xarray to open and visulize on a basic map projection. The data is obtained from the THREDDS Data Server (TDS) utilizing OPeNDAP. 

## Motivation

This cookbook will walk you through obtaining a dataset from the [NCEP/DOE Reanalysis II](https://psl.noaa.gov/data/gridded/data.ncep.reanalysis2.html) data through the TDS utilizing the OPeNDAP. The data set will be opened with Xarray and visualized on a map. 

The workflow used to open and visualize this dataset can be applied to a variety of datasets hosted on the TDS.

## Authors

[Erin Rhoades](https://github.com/erin6541)

### Contributors

<a href="https://github.com/ProjectPythia/cookbook-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/cookbook-template" />
</a>

## Structure

This cookbook is condensed into one section with links throughout to references and documentation. 

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:


1. Clone the `https://github.com/erin6541/xarray-cb` repository:

   ```bash
    git clone https://github.com/erin6541/xarray-cb.git
   ```

1. Move into the `xarray-cb` directory
   ```bash
   cd xarray-cb
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate xarray-cb
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
