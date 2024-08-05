# ContinuousAssociationRDS

This repository contains the code to produce the results for Malatesta et al. "Inferring bivariate associations with continuous data from studies using
respondent-driven sampling". In this paper, we develop a randomization test (Semi-parametric randomization test for continuous association (SPRTCA)) for respondent-driven sampling (RDS) to test for bivariate association when one or both variables are continuous. This repository contains code to run the simulations and generate plots included in the manuscript. Additionally, we provide an Rmarkdown document that walks through an example of applying SPRTCA to a simulated RDS data set. 

## Files

#### `\example` 
This directory contains `SPRTCA_example.Rmd` that includes code and documentation for using SPRTCA. We also provide a simulated data set `example.csv`. We walk through how to run SPRTCA with this data set. 


#### `\sim` 
This directory contains code for simulating RDS data, code to run the simulation settings we included in the paper, and code that plots all simulation results. 

## Contact

For questions, please contact:

Samantha Malatesta (<samalate@bu.edu>)