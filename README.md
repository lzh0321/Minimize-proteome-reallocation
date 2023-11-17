# Minimize proteome reallocation
The **MORP** is an algorithm based on the enzyme-constrained genome-scale metabolic model. The MORP is the prediction that when the condition changes, the cell responds based on the **m**inimization **o**f **r**eallocation of **p**roteome principle. The method calculated the minimal the sum of absolute differences between previously and currently simulated enzyme usage fluxes, from which the intracellular enzyme usage distribution can be obtained after condition change. 

# Applicable scenarios and conditions
scenarios:
Metabolic changes caused by environmental perturbations or genetic alterations.
conditions:
1.Known the enzyme usage fluxes before condition change.
2.Known the constraints of the model after condition change.
