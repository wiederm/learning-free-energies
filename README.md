# tautomer-data
This repository includes the data and code to repdoduce the figures in the main text of the manuscript 'Teaching free energy calculations to
2 learn from experimental data'.

# Data

## Dataset

The original data used for this study was taken from https://github.com/WahlOya/Tautobase. 
The experimental data is included in `data/ani_tautobase_subset.txt`, which includes the name of the tautomer pair, the SMILES strings defining the two molecules and the experimental free energy difference in kcal/mol.

### Relative alchemical free energy results

Results are given in the `calculated` directory.
The results for the RAFE calculations using ANI-1ccx are deposited in the file `AlchemicalANI1ccx_kT.csv`, including the name of the tautomer pair, the free energy estimate and the free energy estimate uncertainty [all in kT].
Results for the RAFE calculations using ANI-2x are given in `AlchemicalANI2x_kT.csv`.

### Optimization

The best parameter files for ANI-2x is located in `optimization/with_regularization/CompartimentedAlchemicalANI2x_best_parameter_set.pt`.

