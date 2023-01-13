# central-galaxies-joint-distributions

This repository contains the material presented in the paper “High-fidelity reproduction of central galaxy joint distributions with Neural Networks”.

* The `models` folder contains the neural networks weights to predict central galaxy joint distributions from their host halo properties.

* The `example.csv` file contains a set of properties of three instances from the IllustrisTNG300-1 data set.

* The `predict_joint_distribution.ipynb` notebook shows an example of how to apply the trained neural networks (from the "models" file) to predict central galaxy properties jointly given the host halo properties (from the example.csv file).

* The `bin_edges.csv` and `bin_means.csv` are auxiliary files to generate the plots in the `predict_joint_distribution.ipynb` notebook.

For further information, suggestions or doubts, please contact:

* Natália Rodrigues: natvnr@gmail.com or natalia.villa.rodrigues@usp.br
* Natalí de Santi: natalidesanti@gmail.com or natali.santi@usp.br

If you use any of the codes or models presented here, please cite the paper.