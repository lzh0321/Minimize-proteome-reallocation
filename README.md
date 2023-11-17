# Minimize proteome reallocation
The MORP is an algorithm based on the enzyme-constrained genome-scale metabolic model. The MORP is the prediction that when the environment is disturbed or the gene changes, the cell responds based on the **m**inimization of reallocation of proteome principle, from which the intracellular enzyme usage distribution can be obtained after condition change. 

In simulation folder, MORP.m calculated the minimal the sum of absolute differences between previously and currently simulated enzyme usage fluxes as the optimal solution after condition change.
