This repository provides a Google Colab notebook for training a machine learning model on small molecules. 
The code showcases how the molecular structures are converted to six different types of chemical fingerprints- Morgan, MACCS, Daylight, Avalon, AtomPairs, Torsion- with RDKit library. Then with this modified dataset of molecular fingerprints and the measured quantity (in this case, absorption energies) the machine learning model is trained with Support Vector Regression algorithm using two kernels - radial basis function kernel and linear kernel. 
At the end for one such case, the correlation between the true values and the model predicted values is plotted. 

The input file is INPUT-ML-Abs.csv. It has to be uploaded on the Files section of Google Colab before running the code. 
