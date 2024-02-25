# SETUP


## Python Environment

The repository is using Jupyter notebooks, which requires basic knowledge how to handle Python environments.

The environments are managed with `conda`, which can be downloaded under:
* Anaconda: https://www.anaconda.com/download
* miniconda: https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html


## Jupyter Lab

If Jupyter should run as own server, it can be installed with:
```bash
# Install Jupyter in current active environment
conda install -c conda-forge jupyterlab ipykernel -y

# Run the server
jupyter lab
```

In case VS Code is used, only the ipykernel package is needed.

Optional packages to beautify things:
```bash
# Install Jupyter Widgets in Jupyter environment (replace base with your environment name)
conda install -n base -c conda-forge jupyterlab_widgets

# Install Widgets in each Kernel environment (if different from Jupyter env)
conda install -n pyenv -c conda-forge ipywidgets
```