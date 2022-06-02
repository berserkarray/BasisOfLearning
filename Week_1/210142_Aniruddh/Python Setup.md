# Python Setup
## Installing Anaconda Navigator
- Go to https://www.anaconda.com/products/distribution and download the required version for your operating system
- Go through the installer, choose the install for Just Me option unless you have administrator privileges
- Set the destination folder (Take care that the path doesn't have spaces or special characters)
- Choose not to register Anaconda to the PATH, but let it become the default Python distribution as it lets your code editor automatically detect Anaconda
- Confirm after the installation that Anaconda Python shows up in your IDE
## Virtual Environment Creation
- Run Anaconda Prompt
- Use the command
```
conda create -n deeplearn python=3.9
```
- 'conda create' is the command to create a new environment
- '-n deeplearn' sets the name parameter of the new environment as deeplearn, feel free to change the name to anything you like
- 'python=3.9' creates the environment with the python version 3.9, as of the moment of writing this file, tensorflow does not work with python 3.10, hence this downgrade has been used
- Now activate the environment so we can install packages
```
conda activate deeplearn
```
### numpy
```
conda install numpy
```
### pandas
```
conda install pandas
```
### matplotlib
```
conda install matplotlib
```
### tensorflow
```
conda install tensorflow
```
### requests
```
conda install requests
```
- Use the command `conda list` to confirm if all these libraries are installed
## Register the kernel
- Jupyter notebook won't detect our new environment directly
- Open a fresh Anaconda Prompt in the base environment
```
(base)$ conda install nb_conda_kernels
(base)$ conda activate deeplearn
(deeplearn)$ conda install ipykernel
```
- Open Jupyter notebooks, make a new folder using the New button on the upper-right side. Then make a new python notebook with your environment - Python [conda env: deeplearn]
- Rename the notebook to anything you like
- To test it out, write these commands in an empty cell and run it
```
import numpy as np
import pandas as pd
import tensorflow as tf
import matplotlib as plt
print(np.__version__)
print(pd.__version__)
print(tf.__version__)
print(plt.__version__)
```
- If the code executes without errors then we were succesful

