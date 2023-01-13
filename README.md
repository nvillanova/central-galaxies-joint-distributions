# central-galaxies-joint-distributions
This repository contains some of the material presented in the paper “High-fidelity reproduction of central galaxy joint distributions with Neural Networks”.

* The "models" folder contains the neural networks weights to predict central galaxy joint distributions from their host halo properties.

* The "example.csv" contains a set of properties of three instances from the IllustrisTNG300-1 data set.

* The "predict_joint_distribution.ipynb" shows an example of how to apply the trained neural networks (from the "models" file) to predict central galaxy properties jointly given the host halo properties (from the example.csv file).

* The "bin_edges" and "bin_means" are auxiliary files to generate the plots in the "predict_joint_distribution.ipynb" notebook.
