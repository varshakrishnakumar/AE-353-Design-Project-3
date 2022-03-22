# AE-353-Design-Project-3
Designing and implementing a Spacecraft with a star tracker

*Version March 2022*

### Abstract
The objective of this exploration is to design, implement, and testing a controller that enables spacecraft to maintain a fixed orientation. This was primarly tested in a Python Jupyter Notebook environment. 

### Instructions for compilation
The main file, *RunSpacecraft.ipynb*, runs on an *ae353* anaconda environment. The instructions given below will set up the user's system for project compilation.

    conda create -n ae353
    
After creating the environment, if Jupyter and Git are not enabled on Anaconda's system, follow the instructions below

    conda activate ae353
    conda config --env --add channels conda-forge
    conda config --env --set channel_priority strict
    conda install python=3 numpy scipy sympy matplotlib
    conda install notebook ipywidgets imageio imageio-ffmpeg pybullet
    conda install git
    
 Next, clone this repository.
 
    git clone https://github.com/varshakrishnakumar/AE-353-Design-Project-3.git
 
 On an Anaconda Powershell terminal, locate the cloned repository and open Jupyter
    
    conda activate ae353
    cd *location of cloned repository*
    jupyter notebook
 
 Upon completion of the instructions, a new Jupyter notebook will be opened. Navigate to *RunSpacecraft.ipynb* to compile the project.
 
