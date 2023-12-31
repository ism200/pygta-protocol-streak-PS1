# pygta-protocol-streak-PS1

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/ism200/pygta-protocol-streak-PS1)

pyglotaran STAR protocol for analysis of time-resolved fluorescence spectra of photosystem I

## Scope

Global and target analysis of transient absorption spectra of photosystem I describing the protocol for Fig.5-6 and Fig.S6-8 of the Cell Press paper DOI: [10.1016/j.isci.2023.107650](https://doi.org/10.1016/j.isci.2023.107650).

## Getting started

[Click here](https://codespaces.new/ism200/pygta-protocol-streak-PS1) to open this repository in a GitHub Codespace. Alternatively, click on the green "Code" button at the top of the repository and select "Open with Codespaces". This will open a codespace with the repository pre-installed and ready to use.

### Local setup

There are many ways to setup a python environment. Here we use conda to create a new environment and install the packages needed to run the notebooks in this repository.

Create a new conda environment for this collection of packages

```shell
conda create --name pygta_protocol python=3.10
conda activate pygta_protocol
```

Now assuming we're in the right pygta_protocol environment, lets use pip to install the requirements from this repository

```shell
pip install -r requirements.txt
# installs pyglotaran, pyglotaran-extras and ipykernel
```
