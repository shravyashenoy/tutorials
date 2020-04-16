# Tutorials
Set of Jupyter Notebooks, along with datafiles, to get started with Scientific Computing in Astronomy  



## Ways to setup Jupyter notebooks 
While Jupyter runs code in many programming languages, Python is a requirement (Python 3.3 or greater, or Python 2.7) for installing the classic Jupyter Notebook.

### Windows
#### Installing python
All the notebooks (.ipynb) would have python version >= 3.6. I recommend you to use the same version of python to avoid compatibility issues.  
Install python from https://www.python.org/ftp/python/3.8.2/Python-3.8.2.tar.xz.  

#### Using Conda or Miniconda
Install Anaconda (it has almost all python packages) from https://docs.anaconda.com/anaconda/install/windows/.
(Read the instructions carefully)  
Then open command prompt or windows shell (press windows button and type 'cmd')  
Enter the following command to install Jupyter notebook  
> conda install jupyter

Enter the following command to run jupyter notebook
> jupyter-notebook

### Linux distribution (includes Ubuntu)
#### Installing python
Python is usually pre-installed in Linux distribution.  
If you are using Ubuntu version > 16 (Skip this part)
If you are using Ubuntu 16.04 then the pre-installed python versions are 2.7.12 and 3.5.2.  
To check your python version, type 'python3' or 'python' if the former doesn't work.
Confirm that your python version is 3.6+.
If not install python from https://www.python.org/ftp/python/3.8.2/Python-3.8.2.tar.xz or use the following command in terminal
> sudo apt install python3.8;

#### Installing Jupyter - Using Conda or Miniconda
Install Anaconda (it has almost all python packages) from https://docs.anaconda.com/anaconda/install/windows/.
(Read the instructions carefully)  
Then open terminal (press CTRL + ALT + T)  
Enter the following command to install Jupyter notebook  
> conda install jupyter;

Enter the following command to run jupyter notebook
> jupyter-notebook;

#### Installing Jupyter - Using python-pip
Install pip using 
> sudo apt install python-pip;

Install jupyter and other important packages using
> pip install --upgrade pip;  
> pip install bs4 requests jupyter scipy astropy matplotlib;

Enter the following command to run jupyter notebook
> jupyter-notebook;

### MacOS
#### Installing Jupyter - Using Conda or Miniconda
Install Anaconda (it has almost all python packages) from https://docs.anaconda.com/anaconda/install/windows/.
(Read the instructions carefully)  
Then open terminal and enter the following command to install Jupyter notebook  
> conda install jupyter;

Enter the following command to run jupyter notebook
> jupyter-notebook;


Using Virtual environment
If you are already using python and have requirements of different python package versions then Virtual environment.
It is helpful for future projects in different versions of python.




// TODO  
// How to create a Virtual environment.  
// Installing jupyter notebooks for Linux distros and Windows.  
// Basic functionalities of jupyter  



