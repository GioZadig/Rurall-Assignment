# Rurall_geo

## Installation Guide

The following guid aims at guiding a new user of conda to create an environment and installing the packages required to launch my Assignment Notebook and reproduce all the results/figures.

### Installing Conda

To install Conda, follow these steps:

1. Download the installer for your operating system from the [official Conda website](https://docs.conda.io/en/latest/miniconda.html).
2. Run the installer and follow the on-screen instructions.

### Creating a Conda Environment

To create a new Conda environment with python v3.12, use the following command:

```bash
conda create --name rurall_env python=3.12
```

If you prefer, replace `rurall_env` with your desired environment name and `3.12` with the desired Python version. For this project, the version `3.12` is needed for package compatibility.

### Activating the Conda Environment

Activate the newly created environment with:

```bash
conda activate rurall_env
```

### Installing Python Packages

To install the required Python packages for the rurall assignment tackled here into the environment, use the following command:

```bash
conda install jupyter numpy metpy matplotlib geopandas datetime contextily scienceplots plotly
```

### Opening the jupyter notebook

To open a jupyter notebook, within the conda environment, launch from the terminal the following command:

```bash
jupyter notebook
```

Then press Crtl + left click on the link appeared in the terminal. A window will open in your default browser. From there, the Notebook will be present and can be opened.

### Additional Resources

For more detailed information, refer to the [Conda documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).