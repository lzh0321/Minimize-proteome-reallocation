# About MORP
The **MORP** is an algorithm based on the enzyme-constrained genome-scale metabolic model. The MORP is the prediction that when the condition changes, the cell responds based on the **m**inimization **o**f **r**eallocation of **p**roteome principle. The method calculated the minimal the sum of absolute differences between previously and currently simulated enzyme usage fluxes, from which the intracellular enzyme usage distribution can be obtained after condition change. 

# Applicable scenarios and conditions
scenarios:
Metabolic changes caused by environmental perturbations or genetic alterations.

conditions:
1.Known the enzyme usage fluxes before condition change.
2.Known the constraints of the model after condition change.

# Required software
Matlab (The MORP was implemented in the matlab)

Gurobi Optimizer (The solution procedure was performed using Gurobi)

# About our study
We used dFBA combined with dynamic MORP (dMORP) to simulate the metabolic shift of Bacillus coagulans from glucose culture to trehalose culture in mixed carbon sources environment. Our simulation suggestted that bacteria tend to minimize proteome reallocation upon environmental changes, which coincided with transcriptomics, proteomics and intracellular metabolite data.

# Contact us
If there are any problems during the use of the MORP, it can be raised in issues.
If there are any suggestion about the algorithm or related research, please contact us (Y12202050@mail.ecust.edu.cn).
