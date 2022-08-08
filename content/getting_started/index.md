---
title: "Getting started"

description: "Start the journey to become a SPARC Guru" 
menu:
  main:
    weight: 1
---
### **Initial setup**
If you have not already done so, clone the GitHub repository onto your local machine into the _SPARC-tutorial_ folder with the following command:

    $ git clone git@github.com:SPARC-FAIR-Codeathon/SPARC-Tutorial.git SPARC-tutorial

The tutorial is contained in a Jupyter Notebook and requires JupyterLab to run. 
#### **If you are familiar with JupyterLab**
Open JupyterLab and navigate to the _SPARC-tutorial_ folder. Open the SPARC-tutorial.ipynb file and follow the tutorial.

#### **If you are not familiar with JupyterLab**
Not sure if JupyterLab is installed on your machine? No worries, we've got you covered! Check out if it is installed on your machine using this command in a terminal:

    $ which jupyter-lab
    
If there is no output, [install](https://jupyter.org/install) JupyterLab with the following command:
    
    $ pip install jupyterlab
    
Once this is done or if you already have JupyterLab installed on your machine simply navigate into the cloned directory and run JupyterLab:

    $ cd SPARC-tutorial && jupyter-lab --LabApp.token='' --no-browser

Once JupyterLab is running you are all set and ready to go! Follow this [link](http://127.0.0.1:8888/lab) to get started and open the SPARC-tutorial.ipynb file.
