# LearnGraphDiscovery

Example code for the paper https://openreview.net/pdf?id=HJOZBvcel

Basic python dependencies needed:
sklearn
theano
keras

##Basic Example
Run Example.py to execute the 39 node model and comparisons to sklearn glasso.

##Evaluating on Other data
The example is simply using our own data generator. In order to evaluate on similar data as in the paper (not the training data generator). You will need to install R, the r-package BDGraph, and rpy2 python package. Then change the variable R_Install in Example.py to True.

##Train and model specification
To train your own model or see the model specifications run Train_39_Node_Net.py

For questions or bug reports please contact eugene.belilovsky@inria.fr
