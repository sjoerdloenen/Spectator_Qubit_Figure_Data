# Spectator_Qubit_Figure_Data
Code to generate figures in spectator qubit paper

To run the code in this directory, make sure you have `uv` [installed](https://docs.astral.sh/uv/getting-started/installation/).

With uv installed, either clone this repository to your pc. 
```
git clone git@github.com:sjoerdloenen/Spectator_Qubit_Figure_Data.git
```
or use the .zip file that can be downloaded from the 4TU database with DOI `10.4121/3929b39b-06e7-45c3-967a-6801e2ea3ae1`. Extract the .zip file and in the extracted repository, run `uv init`. Then download the pyproject.toml file (also available from the same DOI as before) and place it in the same directory extracted repository. 

Go into the respository and run
```
uv sync
```
Depending on the availability of the packages on your platform it might need some time to build, just let it run.
This should be enough to set everything up, including all packages and python version.

I have used VScode to run the jupyter notebooks. To run the notebooks with the uv environment created above, open the just cloned `Spectator_Qubit_data_and_code` folder in vscode. When opening a jupyter notebook, select as a kernel ".venv (Python3.13.2) .venv/bin/python". 
You might need to install some basic extensions in vscode if you have not yet done so.
