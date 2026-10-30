# Pleiades

This repository contains a Jupyter notebook for identifying candidate members of the Pleiades star cluster using Gaia data.

## Method
The notebook:
- Loads a CSV catalog.
- Removes rows with missing values in the required columns.
- Selects candidate members using proper motion (`pmra`, `pmdec`) and parallax.
- Plots a vector point diagram and a color–magnitude diagram.

## Requirements
- Python 3
- pandas
- numpy
- matplotlib

## Data
The notebook expects the CSV file to be available in the same folder as the notebook. Update `file_name` in the notebook if the CSV filename is different.

## Run
Open `pleiades.ipynb` in Jupyter Notebook or JupyterLab and run the cells from top to bottom.
