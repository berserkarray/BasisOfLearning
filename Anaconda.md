
# <u> Anaconda </u>

# What is Anaconda?
Anaconda is an open source handy toolkit for dvelopers. It makes job easy for the developers by enabling them to create specific <u>Working Environments</u> and work in them.


 ## But What Is Working Environment?
 Let's understand this with an easy example. Let's say you are designing a house. Every room has its Environment, and according to the nature of that Environment, we add different items to that room. For example, In Kitchen, we will install a sink and gas stove and additional shelves for utensils and vegetables; just like this, we will install different items in our bedroom and living room.
Now think of this as a developer. A developer is working on various projects simultaneously, and they'll need different packages for different projects. With the help of Anaconda, they can create different **Working Environments** with these different packages that they can access anytime. They'll not have to install these packages every time they switch from one project to another; instead, they switch from one Environment to the other, and they will easily have access to all these packages.
They can also modify these **Working Environments** by adding, removing, or updating any package anytime.

---

# Installing Anaconda.

* Search **Anaconda Install** in your Web Browser.
* Click on Anaconda Distribution link that appears.
* A download option appears on the right part of your screen. Click on download button and wait till it downloads.
* Click on the exectable file which is downloaded and follow simple steps that will follow on screen. Just make sure about the following:
  + While installing select Install for **Just Me** option.
  + Select **<u>Add Anaconda to my PATH environment variable</u>**.
+ Now wait till it installs and then we can work with Anaconda Prompt.
---
# Working in an Environment in Anaconda 
## Creating an Environment
Open the Anaconda command prompt. You'll be direct to a base environment in Anaconda.  
To setup a new Environment, type **"<u>conda create -- name NAME python version</u>"** (without inverted commas)  
Here, NAME is the name of the environment you want to create and Python version will specify which version of pyhton you want to work with in this environment.  
*for example:* ***<u>conda create --name basisoflearning python=3.9</u>*** will create an environment named 'basisoflearning' which will work with python 3.9  
### <u>To enter the environment</u>, 
type ***<u>conda activate basisoflearning</u>*** and you'll enter basisoflearning environment.
### <u>To install any package in the Environment</u>,  
we will have to give different commands to download different packages in Anaconda which are easily available on the web.  
*for example :*  to install NumPy we can give command ***<u>conda instll -c anaconda numpy</u>***. this will install numpy i the environment.

### <u>To exit the environment</u>,
type ***<u>conda deactivate</u>*** and you'll head out of that environment.

---   

## Other Important Commands Examples.
  

* ***<u>conda list</u>*** command fetches us list of all the packages installed in the environment.
* ***<u>conda update numpy</u>*** will update numpy library to its latest version.
* ***<u>conda env list</u>*** gives list of all the environments created on the system.