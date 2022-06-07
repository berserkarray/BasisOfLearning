## Basis Of Learning##
SnT project 2022

## step 1- Installing anacoda ##
download anaconda distribution from https://www.anaconda.com/download/#windows
install with all the packages.

## conda installation ##
Open anaconda navigator 
In the anaconda navigator open powershell prompt there run the following commands 
         conda -V
it shows the version of conda installed on the windows

## creating virtual environments in conda ##
           conda create -n name_of_the_file python=3.9
this creates a Venvironment 

## to activate VEnvironment

          conda activate deeplearn

## to install numpy,pandas,matplotlib

          conda install numpy
          conda install pandas
          conda install matplotlib


## to check the version of the various libraries

         print(numpy.__version__)
         print(pandas.__version__)
         print(matplotlib.__version__)
         
## completed with the anaconda distribution and created environments 