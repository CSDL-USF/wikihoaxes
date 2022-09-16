# Code and data for [A Elebiary, GL Ciampaglia. 2022](https://wikiworkshop.org/2022/papers/WikiWorkshop2022_paper_30.pdf)

This repository contains a Jupyter notebook that replicates the coda and data for the paper.

# 1. Installation

The notebook was written in Python 3. A number of dependencies are to be
installed before running it. A list of package requirements is provided. The
simplest method is to run a package manager such as pip or conda. It is
recommended that all dependencies are installed in a separate Python
environment.

The best way to do so is to use the Miniconda, which is a small bootstrap
version of the largest Anaconda Python distribution. Miniconda is available for
most major operative systems (Windows, Linux, MacOS) 

1. Download Miniconda from here: https://conda.io/miniconda.html
2. Follow the installation instruction for your platform:
   https://conda.io/projects/conda/en/latest/user-guide/install/index.html
3. Clone or download this repository
```
git clone https://github.com/CSDL-USF/wiki-workshop-2022-elebiary-ciampaglia.git
```
4. Open a terminal and run:
```
    cd twitch-overload
    conda env create --file environment.yml
    conda activate twitch-overload
```

## plots replication
plots.ipynb: to recreate the plots found in the paper

## data generation
data.ipynb: to generate the data used within plots.ipynb

## data link
The following link contains the data required to run plots.ipynb & data.ipynb
https://drive.google.com/drive/folders/1zrOTxxRABRgM741k1pb2RJ7oNSMGBIh8?usp=sharing

## scripts
The directory scripts contains .py files meant to run on Wikimedia's Toolforge server.
For information on how to access Toolforge, consult the following link and check their quickstart guide:
https://wikitech.wikimedia.org/wiki/Portal:Toolforge

#### check environment.yml for the required python libraries

