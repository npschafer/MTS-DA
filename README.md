# MTS-DA
## Data augmentation for multivariate time series classification
or
## How do you make a ghost jump?

Can time series classifiers benefit from synthetic data augmentation? In the notebooks in this repository, I explore the application of synthetic data augmentation using weighted dynamic time warping barycenter averaging to improving the performance of a 1-NN DTW-based classifer for multivariate time series.

Notebooks:
1. [summary.ipynb](notebooks/summary.ipynb) - An overview of the methodology and results
1. [syntheticdatageneration.ipynb](notebooks/syntheticdatageneration.ipynb) - Synthetic data generation
1. [testandplotclassificationaccuracy.ipynb](notebooks/testandplotclassificationaccuracy.ipynb) - Testing the classification accuracy as a function of the degree of data augmentation
1. [rawtimeseriesvisualization.ipynb](notebooks/rawtimeseriesvisualization.ipynb) - Plotting raw time series data
1. [3DtSNEvisualizations.ipynb](notebooks/3DtSNEvisualizations.ipynb) - Plotting a 3D t-distributed stochastic neighbor embedding of baseline and augmented datasets
