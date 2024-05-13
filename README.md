# Northwestern Research Computing Services - Distance and similarity - (Python) Workshop

## General information
Clustering samples correctly requires accurate measures of similarity. Depending on your data type, we will explore several ways to compute similarity (or distance). Then, we will use hierarchical clustering to group data points. At the end, you will make a clustering dendrogram. 

## Preworkshop setup
Please have a way to run a Jupyter notebook. 
#### Run on Google colab
One option is to use [Google colab](https://colab.research.google.com/). If you have access, then you are done with the pre-work! 

#### Run on your computer 
Another option is to run the Jupyter notebook locally. Please install [Anaconda or conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). The python packages used in this demonstration are: numpy, scipy, matplotlib, and jupyter.

You can also create a new environment named "dataanalysis" with the necessary python packages. In your terminal:

```console
conda create -n dataanalysis python=3.10 numpy scipy matplotlib jupyter
```

The terminal will show the creation of an environment, including downloading these python packages. For more [detailed information about conda environments](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment). 

To enter the environment:

```console
conda activate dataanalysis
``` 

To exit the environment:
```console
conda deactivate dataanalysis
```

## The day-of
#### Run on Google colab
Make a copy of the linked colab notebook so that you can edit!

#### Run on your computer
Please enter the environment and launch jupyter notebook. In the terminal:  

```console
conda activate dataanalysis
jupyter notebook
``` 


### References
https://docs.scipy.org/doc/scipy/reference/spatial.distance.html 
