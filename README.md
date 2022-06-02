# **Basis Of Learning**
>    SnT Project -2022 

## **Getting Started**
### ***Installing Anaconda***
Getting Started with Python Anaconda Distribution 

Download Python Anaconda Distribution
> [Download Here](https://www.anaconda.com/download/#windows)

 Find the Anaconda Navigator application. 
 This is the go-to application for using all of the capabilities of Python Anaconda distribution.


### Managing Python Packages

> — Conda Installation
>>Select the Environments tab located on the left side of the application.
On the base environment, click on the play icon. Then, use the drop down menu to select Open Terminal.
If you need to install other packages, you can repeat these steps.
### ***Creating Virtual Envinorments***

Like many other languages Python requires a different version for different kind of applications. The application needs to run on a specific version of the language because it requires a certain dependency that is present in older versions but changes in newer versions. Virtual environments makes it easy to ideally separate different applications and avoid problems with different dependencies. Using virtual environment we can switch between both applications easily and get them running.

You can an environment using virtualenv, venv and conda. 

Conda command is preferred interface for managing installations and virtual environments with the Anaconda Python distribution.

Step 1: Check if conda is installed in your path.

Open up the anaconda command prompt and type

    conda -V

If the conda is successfully installed 
you can see the version of conda.


Step 2: Update the conda environment 

Enter the following in the anaconda prompt.

    conda update conda

Step 3: Set up the virtual environment

Type conda search “^python$”  to see the list of available python versions.

Now replace the envname with the name you want to give to your virtual environment and replace x.x with the python version you want to use.

    conda create -n envname python=x.x anaconda

Step 4: Activating the virtual environment

To see the list of all the available environments use command 

    conda info -e

To activate the virtual environment, enter the given command and replace your given environment name with envname.

    conda activate envname


 

 When conda environment is activated it modifies the PATH and shell variables points specifically to the isolated Python set-up you created.

 

Step 5: Installation of required packages to the virtual environment


Type the following command to install the additional packages to the environment and replace envname with the name of your environment.

    conda install -n yourenvname packagename

Step 6: Deactivating the virtual environment

To come out of the particular environment type the following command. The settings of the environment will remain as it is.

    conda deactivate


Step 7: Deletion of virtual environment

If you no longer require a virtual environment. Delete it using the following command and replace your environment name with envname

    conda remove -n envname -all 

### **Using Jupyter Notebooks**
**Launching the Jupyter Notebook:**

Jupyter Notebook is a web-based tool, so it requires your web browser to work.

 To open Jupyter Notebook, you can search for the application on your computer and select it. Alternatively, you can open it up from your terminal or command line with the following command:

    jupyter notebook


***Understanding the Jupyter Notebook Interface:***



How to navigate the Jupyter Notebook interface.

***The Notebook Name:***

 The name of your notebook is next to the Jupyter Notebook logo in the top left corner of your screen:

![image](https://miro.medium.com/max/1400/0%2ADoCDP8q8teCrKmb_)

By default, the notebook name is set to Untitled. You can change this name by clicking it.


Next to the name of your notebook, you’ll notice a checkpoint. Jupyter Notebook automatically saves when you edit the notebook cells. The checkpoint simply shows the last time the notebook was saved.

***The Menu Bar:***

![image](https://miro.medium.com/max/1400/0%2Aj5uNXY3arianSJi5)

The Menu Bar contains different menus that you’ll be using when working within the notebook.

**File:** can access file options. 

**Edit:**  To edit existing cells. 

**View:**  To personalize the appearance of your notebook

**Insert:** This is used to insert new cells

**Cell:**  used to run a cell after you have entered Python code. You can choose to run a specific cell, the cell below it, or the cell above it.

**Kernel:** The engine of the notebook.

options in the Kernel menu:

**Interrupt:** This is used to stop a cell that is currently running. 

**Restart:** This is used to restart the Kernel. 

***Restart & clear output:*** This restarts the Kernel and clears the output from the notebook. 

**Restart & run all:** This option will restart the Kernel and run all the cells in one go.

**Reconnect:** Sometimes a kernel will die for no particular reason. When this happens you can reconnect using this option.

**Shut down:** This is used to shut down the kernel and stop all processes

**Change kernel:** When you have more than one anaconda virtual environment installed, you can switch between different kernels.

**Widget:** Widgets are used to build interactive GUIs on your Notebook

**Help:** This is used to find resources when working with Jupyter Notebook, or the key libraries that come with it

The Command Icons

![command icon](https://miro.medium.com/max/1400/0%2ABOy_aTKrPw1a5t8F)

This is another critical area when working within a Jupyter Notebook. These icons allow you to perform certain functions on cells or on a single cell.

***Cells:***

![cell](https://miro.medium.com/max/1400/0%2AFm0RReHc5O4PkO_i)

 this is where you run Python code. .

Running Python Code

 you run it by clicking the run button from the command palette above.

There is a shortcut, use ‘*Shift+Enter*’ to run a cell and add a new cell below.

***Markdown:***

 Used to write plain text. 

You can Manuplate size of text using "*#*"

To bold text surround your text double asterixis (**).

For italics an underscore (_) before and after the words.

***Raw NB Convert:***

Used to convert the notebook file to another format.


## **Assignment-1**

>[Python Basics](Python.ipynb)

>[Pandas Basics](Pandas.ipynb)

>[Numpy Basics](Numpy.ipynb)

>[Matplotlib Basics](Matplotlib.ipynb)
