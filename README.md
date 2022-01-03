# Machine Learning and Statistics Project repository

### Machine Learning and Statistics 2021 GMIT
### Orla Higgins G00364860
##

The purposes of this repository is to provide an overview of the scipy.stats and scikit-learn libraries in Python. Using Markdown and Python, the scipy-stats jupyter notebook describes the scipy.stats library and contains an ANOVA test. The scikit-learn jupyter notebook describes the scikit-learn library and looks in detail at three machine learning algorithms from the package. 
***


## Repository Contents 
Name | Content
------------ | ------------- 
  scipy-stats.ipynb | Text file containting table of contents of repository
  scikit-learn.ipynb | Jupyter Notebook File containing text and Python code describing Box Plots 
  requirements.txt | list of programmes and packages required to run the repository 
  datasets/ | folder containing dataset in the form of CSV files used within the notebooks
  images/ | folder containing images used within the notebooks
  README.md | Instructions on how to use the repository
  .gitignore |  


### scipy-stats.ipynb

You can view the **scipy-stats.ipynb** notebook in static form by clicking the following image:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/orlaith17/MachineLearning-StatisticsProject/blob/main/scipy-stats.ipynb)

You can view the notebook in dynamic form by clicking the following image: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/orlaith17/MachineLearning-StatisticsProject/HEAD?labpath=scipy-stats.ipynb)

### scikit-learn.ipynb
You can view the **scikit-learn.ipynb** notebook in static form by clicking the following image:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/orlaith17/MachineLearning-StatisticsProject/blob/main/scikit-learn.ipynb)

You can view the notebook in dynamic form by clicking the following image: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/orlaith17/MachineLearning-StatisticsProject/HEAD?labpath=scikit-learn.ipynb)

***

## Running the Notebooks

### Run notebook locally

1. Download [Anaconda]().
2. Download [cmder]() if on Windows.
3. Run `jupyter lab`. 

To run the notebook on your machine you will need to have Juptyer installed. If you have the anaconda distribution you should already have Jupyter installed. If not running anaconda and you have pip installed you can download Jupyter using the pip install command in the command line like below.

**pip install jupyter**

Now that you have Jupyter installed, you can download the notebook. To launch the notebook app navigate to the directory the file is stored in on the command line and enter the jupyter notebook command as below:

**jupyter notebook**

The jupyter notebook app should launch in your browser and should contain the contents of the directory you were in. Simply select either of the .ipynb notebook files to open in the browser.

This notebook is designed to be executed from start to finish. All code cells build on previous cells within the notebook and variables are called from previous cells. If you receive an unexpected error codes make sure that the code has been run in order. Code can be run using the keyboard shortcut Shift + Enter.

#### Dependencies
If running the notebooks on your machine, your will need a version of python installed. The notebooks were created and tested using Python version 3.8.3, but may work with other versions. All package dependencies are listed in the requirements.txt file. To install all packages you can use the below command from within the project directory that contains the requirements.txt file.

**pip install -r requirements.txt**

### Run Remotely
If you do not wish to run the notebooks on your machine you can use either the NB Viewer or the Binder links below. NB viewer allows for view only access to the notebook from within the browser while Binder allows you to execute the code cells remotely from the browser.

This eliminates the need to install any further software or packages on your machine.
#### Viewing the notebooks via NBViewer

Both notebooks are also available via NBViewer. This renders the notebook so that it can be accessed via a URL, although the cells cannot be interacted with like in a live Jupyter Notebook. You can find the NBViewer links via the links above.

#### Viewing the notebooks via Binder

Similar to NBViewer, Binder allows us to host our Jupyter Notebooks online while allowing users to still interact with the cells. You can find the URLs for the two notebooks in Binder via the links above.















