# Time-Varying-Treatments
This repository contains project files and R scripts illustrating two approaches to causal inference with time-varying treatments
Time-varying treatments and confounders frequently arise in clinical studies where both treatment allocations and patient covariates can evolve over repeated follow-up visits. Traditional regression methods can yield biased estimates in these settings, particularly when certain time-dependent confounders (1) are themselves influenced by prior treatment decisions, and (2) influence subsequent treatment choices. To address these issues, two key analytic frameworks have been developed:

G-Formula (G-Computation): This approach models both the outcome and covariate processes over time, thereby enabling the estimation of counterfactual outcomes under various hypothetical treatment regimes.
Inverse Probability Weighting (IPW): This technique weights individual observations by the inverse of the probability of receiving the observed treatment at each time point, thus creating a pseudo-population in which treatment is as if randomly assigned.
In this project, these methods are applied to two distinct longitudinal datasets: