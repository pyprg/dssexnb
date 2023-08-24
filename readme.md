# Installation
## General
This folder holds **Jupyter Notebooks** demonstrating features of DSSEX (https://github.com/pyprg/dssex) &mdash; experimental parts of a **D**istribution&nbsp;**S**ystem&nbsp;**S**tate&nbsp;**E**stimator (DSSE).

Installations of Python, Jupyter and DSSEX are required in order to use these **Jupyter&nbsp;Notebooks**.
## Python
- download **Python** from https://www.python.org/downloads/
- install it according to instructions
## Create a Virtual Environment
1. on **Windows** open a cmd-shell in a folder where you want to place a virtual environment
1. in order to create a virtual environment named **dsseenv**, run command
>```py -m venv dsseenv```
1. activate the virtual environment with command
>```dsseenv\Scripts\activate``` 
1. install jupyter (https://jupyter.org/) run
>```pip install jupyter```
## Install DSSEX
In the activated virtual environment **dsseenv** from previous paragraph (item 3.) issue command:
>```pip install dssex```
# Run **Jupyter Lab**
In the activated virtual environment **dsseenv** paragraph **Create a Virtual Environment** (item 3.) issue command:
>```jupyter lab```

When successful, the command will finally open a browser with **Jupyter Lab** Web-UI.

Use the file browser (Ctrl+Shift+F) of Jupyter Lab for navigation to e.g. dssexnb/powerflow.ipynb and open it.