# cecam-mosdef-workshops
Workshops for the Molecular Simulation and Design Framework

# How To Use:

## Use binder:
Click: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chrisjonesBSU/cecam-mosdef-workshops/main)   

This launches a remotely-hosted Jupyter Notebook instance with everything ready-to-go. This is recommended for anyone on a Windows machine, or anyone who does not already have the anaconda package manager installed. Although, you can use this link regardless.


## Use Locally:
If you are on a MacOS or Linux machine, and already have the anaconda package manager installed, you can choose to build the environment and run the notebooks locally.

In your terminal run:


```
git clone git@github.com:chrisjonesBSU/cecam-mosdef-workshops.git
cd cecam-mosdef-workshops
conda env create -f environment.yml
conda activate mosdef
cd notebooks
jupyter lab
```

