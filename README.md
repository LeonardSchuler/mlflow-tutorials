# Getting Started
Before you proceed, make sure you have conda installed.
```
conda --version
```
You can then create the required conda environment using:
```
conda env create -f environment.yml
```
After the environment is successfully created, execute:
```
conda activate mlflow-jupyter
```
We need to start MLFlow. To do that execute:
```
mlflow server
```
Open a new terminal, change directory to this repo, and run
```
conda activate mlflow-jupyter
jupyter lab
```
Open the tutorial notebook in Jupyter lab and proceed with the tutorial.


# Uninstall
You need to first stop your running MLFlow and Jupyter lab servers.
To do this go to the running terminals and hit Ctrl+C.

The following command deletes the previously created conda environment.
```
conda env remove -n mlflow-jupyter
```
