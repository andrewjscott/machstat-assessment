# Machine Learning and Statistics

This repository was created for the module Machine Learning and Statistics as part of a HDip in Computing in Data Analytics course. 

The repository contains two folders: Machine Learning Project and Practicals. There is also a requirements.txt file which contains the names of the Python packages needed to run these notebooks.

### Machine Learning Project
***
This folder contains a Jupyter notebook called keras-anomaly.ipynb which looks at and expands upon a ["Timeseries anomaly detection using an Autoencoder"](https://keras.io/examples/timeseries/timeseries_anomaly_detection/) example provided by Keras. It contains Python code which creates and demonstrates how a deep learning model can be used to detect anomalies in a dataset, as well as markdown text explaining the concepts and code. 

### Practicals
***
This folder contains three Jupyter notebooks, each created to answer exercises associated with the Machine Learning and Statistics lecture series. All notebooks contain both Python code and Markdown text further explaining the code.   

The first notebook is called 01-stats-exercise.ipynb and contains three exercises. The first exercise concerns the Lady Tasting Tea problem and probability statistics, while the second exercise expands shows how to use the Python package scipy to help to simulate the same problem. The third exercise expands upon the example given by scipy regarding t-tests. 

The second notebook is called 02-models-exercises.ipynb and contains two exercise. The first exercise uses numpy and matplotlib to plot the absolute function and explains why the absolute function is not typically used for line fitting. The second exercise uses Numpy Polyfit, Scipy Optimize, and Scipy Curve Fit to fit a straight line for a dataset and discusses whether a straight line is a suitable choice for those data.

The third notebook is called 03-parameters-exercises.ipynb and contains one exercise which involves using numpy's polyfit to fit polynomials to two datasets. 

## How to use
***
Rendered versions of the notebooks can be viewed by clicking on the badges below:

keras-anomaly.ipynb - [![nbviewer](https://img.shields.io/badge/jupyter_notebooks-nbviewer-purple.svg?style=flat-square)](https://nbviewer.org/github/andrewjscott/machstat-assessment/blob/main/Machine%20Learning%20Project/keras-anomoly.ipynb)      

01-stats-exercise.ipynb - [![nbviewer](https://img.shields.io/badge/jupyter_notebooks-nbviewer-purple.svg?style=flat-square)](https://nbviewer.org/github/andrewjscott/machstat-assessment/blob/main/Practicals/01-stats-exercise.ipynb)     

02-models-exercises.ipynb - [![nbviewer](https://img.shields.io/badge/jupyter_notebooks-nbviewer-purple.svg?style=flat-square)](https://nbviewer.org/github/andrewjscott/machstat-assessment/blob/main/Practicals/02-models-exercises.ipynb)     

03-parameters-exercises.ipynb - [![nbviewer](https://img.shields.io/badge/jupyter_notebooks-nbviewer-purple.svg?style=flat-square)](https://nbviewer.org/github/andrewjscott/machstat-assessment/blob/main/Practicals/03-parameters-exercises.ipynb)       


The notebooks can also be edited and/or run on your local machine using the following steps:

1. Install [Python](https://www.python.org/downloads/) and [Jupyter](https://jupyter.org/install) if you don't already have them installed.
2. Clone this repository by running the following code on your command line: ```git clone https://github.com/andrewjscott/machstat-assessment.git```  
3. If you already have Python installed, you may wish to navigate to the cloned folder and launch a virtual environment by first running the following: ```python -m venv venv``` and press return, and then run: ```.\venv\Scripts\activate.bat``` 
4. Install the required modules by running the following code on your command line: ```pip install -r requirements.txt``` (Running this in a virtual environment ensures these requirements wont interfere with your existing installed packages.)  
5. Launch Jupyter by running the following code in your command line ```jupyter lab```
6. Jupyter should now launch in your web browser. Navigate to the notebook you wish to view. 
7. In the menu bar, click on 'Kernel' and then click 'Restart and Run All Cells'.
