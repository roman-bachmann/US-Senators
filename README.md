# Learning US senate voting behavior from bill sponsorship profiles
Final project of the EPFL EE-558 Network Tour of Data Science class

## Overview
Our code is organized as such:

- `project.ipynb`: The main Jupyter notebook
- `Report.pdf`: The final report
- `data/`: Directory containing scraped and cleaned data sets
- `plots/`: The saved plots used in the report
- `lib/`: Graph CNN implementation from https://github.com/mdeff/cnn_graph
- `notebooks/`: Additional undocumented Jupyter notebooks used during data exploration, data gathering and model construction.

Some of the files needed exceed the github allowed filesize. We hosted them on Git Large File System (https://git-lfs.github.com/). To download them, install Git LFS and pull using `git lfs pull`.

## Requirements
To run the Jupyter notebooks, following packets are required:

- altair==2.3.0
- matplotlib==3.0.1
- networkx==2.2
- numpy==1.15.4
- pandas==0.23.4
- pyunlocbox==0.5.2
- scikit-learn==0.20.1
- scipy==1.1.0
- seaborn==0.9.0
- tensorflow==1.12.0
