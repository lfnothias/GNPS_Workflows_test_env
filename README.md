# GNPS_Workflows_test_env
Repo for running in a Binder server the converter scripts from the Feature-Based Molecular Networking (FBMN) on `GNPS_Workflows`.

## Progenesis QI files conversion for FBMN on GNPS
This notebook converts your Progenesis QI files into a FBMN suitable format (MZmine-like). This is a temporary solution until the fixes are incorporated into the next GNPS release. Note that the script does not support "groups".

### Run the notebook
Click on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/GNPS_Workflows_test_env/HEAD?labpath=FBMN_Progenesis_QI_file_converter.ipynb) to run the notebook.

### Instructions

- Step 1 - Open the navigation panel in Jupyter lab environment.
- Step 2 - Upload your files in the `reference_input_files/` folder (left panel, you can drag and drop the files).
- Step 3 - Specify the names of your input files (.CSV and .MSP) in the cell below and run the cell.
- Step 4 - Run the cell below.
- Step 5 - Download the converted files from the `output_files`. Important: make sure to select 'MZmine' in the FBMN workflow when using these input files.

![](drag_drop_input_files.png?raw=true)


