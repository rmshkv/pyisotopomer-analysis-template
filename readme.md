# Installation

First, clone this repository:

```
git clone https://github.com/rmshkv/pyisotopomer-analysis-template.git
```
To install a pre-made environment with everything you need and a compatible version of pyisotopomer, run:

```
conda env create -f environment.yml
```

By default, the new environment will be called `pyisotopomer-analysis`. You can change the name by editing the `name` field in `environment.yml`.

# Running

Activate the conda environment that you created above, then open Jupyter Lab:

```
conda activate pyisotopomer-analysis
jupyter lab
```

This should open a browser window with Jupyter Lab. From there, open `analysis_template.ipynb`. The notebook contains instructions for how to input paths to your data, standards, etc. You'll probably want to make multiple copies of the file to analyze different chunks of your data later on.