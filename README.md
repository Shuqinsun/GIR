This repository contains the implementation of the double iteratively reweighted algorithm for solving constrained nonconvex group sparsity optimization problem. 
For further details on the problem and the algorithm, please refer to our paper:

run.p  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Run three sets of numerical experiments 1.-3. for comparasion separately and store the data correspondingly.

1.&nbsp;contrast_runcode_ADMM_GADMM.p             &emsp;&emsp; Code for numerical experiments of algorithms IR_{ADMM}  and GIR_{ADMM}

This comparative experiment uses Algorithms IR_{ADMM} and GIR_{ADMM} to solve different models to demonstrate the advantages of the proposed models.

ADMM_LY_P_S.p

gADMM_in.p

objective_function.p

constraint_function.p                        &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Subroutine for contrast_runcode_ADMM_GADMM.p

2.&nbsp;contrast_runcode_GADMM_PAN_phix.p         &nbsp;&nbsp;&emsp; Code for numerical experiments of algorithms  GIR_{ADMM} and SPA

This numerical experiment solves the same model using different algorithms; the model belongs to the group sparse optimization problem, and its constraint part does not include non-convex losses.

gADMM_inphix.p

objective_function.p

constraint_functionphix.p

Lpphix.p

Lp_penaltyphix.p

explicitMatrix.p

f_C_log.p

proximal_operator_for_logsum_2.p

r2_vector.p

r2_one_dimension.p                           &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Subroutine for contrast_runcode_GADMM_PAN_phix.p 

3.&nbsp;contrast_runcode_Panlili_GADMM.p           &emsp; Code for numerical experiments of algorithms  GIR_{ADMM} and SPA

This numerical experiment also solves the same model using different algorithms; the model belongs to the group sparse optimization problem, but its constraint part includes non-convex losses.

gADMM_in.p

objective_function.p

constraint_function.p

Lp.p

Lp_penalty.p

explicitMatrix.p

f_C_log.p

proximal_operator_for_logsum_2.p

r2_vector.p

r2_one_dimension.p                           &emsp; &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Subroutine forcontrast_runcode_Panlili_GADMM.p 

