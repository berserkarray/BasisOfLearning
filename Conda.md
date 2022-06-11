# BasisOfLearning
Week 1

# Working with conda environments

Firstly install anaconda from https://www.anaconda.com/products/distribution#windows

Open a terminal window and type 
#### conda --version
Conda displays the number of the version that you have installed.

Update conda to the current version. Type the following:
#### conda update conda

# Managing Environments

Open conda command prompt-

Create a new environment and install a package in it.

We will create a new anaconda package say 'deeplearning'.
Using the following command in conda command promp
#### conda create --name deeplearning

To use, or "activate" the new environment, type the following:
#### conda activate deeplearning

To install package to given environment we will type:

#### conda install -n deeplearning python




