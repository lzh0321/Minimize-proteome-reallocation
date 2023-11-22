# About MORP
The **MORP** (**M**inimization **o**f **R**eallocation of **P**roteome) algorithm is built upon the enzyme-constrained genome-scale metabolic model. It predicts that when conditions change, cells respond based on principle of minimizing the reallocation of proteome. This method calculates the sum of absolute differences between previously and currently simulated enzyme usage fluxes, with the goal of obtaining the intracellular enzyme usage distribution after the condition change. 

# Applicable scenarios and conditions
scenarios:
Metabolic changes caused by environmental perturbations or genetic alterations.

conditions:
1.Known the enzyme usage fluxes before condition change.
2.Known the constraints of the model after condition change.

# Required software
Matlab (The MORP is implemented in the matlab)

Gurobi Optimizer (The solution procedure is performed using Gurobi)

# About our study
We use a combination of dynamic Flux Balance Analysis (dFBA) and dynamic MORP (dMORP) to simulate the metabolic transition of Bacillus coagulans from a glucose culture to a trehalose culture in a mixed carbon sources environment. Our simulation results indicate that bacteria tend to minimize proteome reallocation in response to environmental changes. These findings are consistent with transcriptomics, proteomics, and intracellular metabolite data.

# Contact us
If there are any problems during the use of the MORP, it can be raised in issues.
If there are any suggestion about the algorithm or related research, please contact us (Y12202050@mail.ecust.edu.cn).
